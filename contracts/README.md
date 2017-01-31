#The service contract

Contract first is the modo off all good API developers.  There are many advantages to this approach but mainly 
* Your api will be more stable (less versions).
* Your api consumer can start the integration work while you work on the implementation.
* You will be able to focus on the business rather the the technology.

By focusing first on the contract you focus on the business case, not the technology.  Your service should serve a business requirement not a technical one.
  
By being business centric you ensure the perenity of your service.  A technical centric service layout or architecture is volatile and will change much more often then if it serves a specific business need.

ReST being the current defacto standard for the web your API defines resources that you should think of as entities.  The http verbs define how you can alter the state of those resources.  