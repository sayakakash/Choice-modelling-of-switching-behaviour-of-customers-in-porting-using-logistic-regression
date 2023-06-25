Choice modelling is a quantitative approach used to understand how customers make choices. It involves creating an econometric or mathematical model to empirically analyze customer decision-making processes. Choice modelling can be applied to various types of choices, such as binomial choices (yes/no decisions) or multinomial choices (choosing between multiple options).

This project focus  on binomial choice modelling related to mobile number porting in India. Mobile number porting allows customers to switch from one service provider to another while keeping their existing mobile number. The process involves requesting a porting code from the current service provider, providing it to the new service provider, and transferring the number within a specified timeframe.


So the generic procedure of  mobile number porting is like that you send request to your service provider that you want to port, and the service provideris mandatorily have to give you a porting code and with that porting code you have to go to the next, new service provider, give that porting code and within some days that particular number gets transferred.But there are certain problems in that, there are certain issues,probably which sometimes hinders you from going from one service provider to another service provider .If you are a very profitable customer or you are a probably a customer who is postpaid .So, if you are a postpaid customer they will call you and they will ask you what happened ?Why are you changing, why do you want to switch from them  to some other service provider?And what kind of facilities they can give you?Is there a service problem because they can improve the service problem and so on?And then, they will also say that, okay,there are new-new offers that are coming up.You can get some discounts in the next billing.So they will give you lots of offerings to make sure that you stay back.So that is something that they do.But when you still say that, I will not go into all these details , they will send you a survey.Probably sometimes they send you a survey or sometimes through that vocal voice based conversation, they take a survey to and ask you that what is the service quality perception,price perception,etc and you give ratings on that.So, now this is something is like exit interview in case of HR problems.So, it is like when somebody is leaving the service provider, why he is leaving.So, when you get this data you can analyze this data to find out that that what are the things that customers who are switchers or customers who are non-switchers think that is important,So what customers value when they are switching.In this context, we can talk about 4 switching barriers.So this is marketing concept.Where we say that, you can also set up certain kinds of switching barriers to make sure that your customer does not go away from you.

Economic switching barriers: These barriers relate to financial factors that hinder customers from switching, such as losing account balances or benefits associated with their current service provider.The moment you try to port from one mobile service provider to another service provider all the balance that you have in your simcard goes nullified and you do not get that facilities.

Social and psychological switching barriers: These barriers are related to customers' social connections and psychological attachment to their current service provider. Factors like having friends, family, or colleagues on the same network can make customers hesitant to switch.This happens in mobile number.That I have all my people in the same network, which is let us say xyz.So, then why will I switch from xyz to somebody else.So that becomes a very major problem and that is something called social and psychological.So, I am habituated with this mobile service provider, I do not want to switch from here to somebody else

Procedural switching barriers: These barriers pertain to the complexity and difficulty of the switching process. If the procedure involves extensive paperwork, permissions, or other hurdles, customers may be discouraged from switching. let us say if you have to take lots of permission from here and there to switch, switch from one place to another place in terms of service provider.If there were mobile number code, then you go and give it to the new mobile number service provider and then they give some code and then you have to again go, go back to the old one and give that number to that old one.And there is lots of paper works in between and blah blah blah.

Option-related switching barriers: This barrier is associated with the availability and attractiveness of alternative options. If customers perceive limited or unappealing options, they are less likely to switch or in some case the option available is the only option.

To analyze the data and understand the factors influencing switching behavior, we can use generalized linear models (GLM) with a binomial logit family. Logistic regression is used to model the relationship between the predictor variables (gender, age, profession, urban/rural status, recipient operator, etc.) and the switching behavior (1 for switched, 0 for not switched).


data dictionary :

SInt: switching intention 

Price: Represents the price or cost associated with the mobile network operator's services.

PSB: Procedural Switching Barrier. It represents a rating or measure of the procedural barriers to switching faced by the individual.

ESB: Economic Switching Barrier. It represents a rating or measure of the economic barriers to switching faced by the individual.

OSB: Operational Switching Barrier. It represents a rating or measure of the operational barriers, including option-related, social, and psychological factors, faced by the individual.

Sat: Overall satisfaction rating provided by the individual. It represents their overall satisfaction with the services of the mobile network operator.

Servqual: Service quality rating provided by the individual. It represents their perception or rating of the quality of service provided by the mobile network operator.

SwBh: Switching behavior. It indicates whether the individual has actually switched their mobile network operator (1 = Switched, 0 = Not Switched).
