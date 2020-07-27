**ASSIGNMENTS**
<hr>

Check your understanding on the topics covered during the first webinar, by going through these assignments.

These are not due and you don't need to submit the answers to us. They are for you to check your own understanding. If you have trouble with any of the technical questions or are unsure of the answer, please post in the channel to get help from a Tech Leader or a Teaching Assistant.

<hr>


**1.** Review the **[slides deck](https://docs.google.com/presentation/d/1-nX-M9ZLGCT20t93sH669gTuH48wu_LbL9YilgpOEFs/edit#slide=id.g8dcbb98f02_0_46)** used during the webinar.

**2.** Explore the articles and source code that the links on the **[slides](https://docs.google.com/presentation/d/1-nX-M9ZLGCT20t93sH669gTuH48wu_LbL9YilgpOEFs/edit#slide=id.g8dcbb98f02_0_46)** direct to.

**3.** Complete the mini quiz **[here](http://quizizz.com/join?gc=4358216)**.

**4.** Create an additional layer of workers with the `move()` method below. What has moved?
```
x = torch.tensor([1,2,3,4,5]).send(bob).send(alice).send(cindy)
x.move(daniel)
```

**5.** Why don’t we need to define a pointer variable when calling `model.send(data.location)`?
