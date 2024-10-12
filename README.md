# Probably

We are Probably from Fayetteville, NC! Both of our members, Andres Ayala-Lagunas and Ethan Patten are third year Computer Science students at NC State. We heard about this challenge through an email and decided that we wanted to go. However, we also had 3 exams earlier the week of the hackathon for our grad classes, so whenever we asked eachother if we were going to be able to make it, we kept telling eachother "probably" (where our team name came from), although we knew internally that we'd make it no matter what. This is Probably!

profile.png

For the actual challenge itself, we had very little background in quantum computing, but a large background in image processing. We had a very "Frankenstein" approach to tackling this challenge. We started by first analyzing the code we were given and exploring why one would choose each particular part (focusing on the encoder and ansatz) through research. After some research, we attempted to learn to implement our own encoders, in which we tried several approaches, but ultimately decided that the AngleEncoder provided to use, with an entanglement depth of 1 was right for us after comparing various test runs. When we saw that the encoder itself did not matter that much, we poured our focus into building an effective ansatz, again starting by seeing what each provided ansatz did and why it could possible be a good pick through both research and our own testing. After that, we took different paths individually, one attempting to craft a completely custom ansatz and the other attempting to modify the ansatz that preformed best, the Cross Orthogonal Ansatz. In attempts to modify the COA, the axis of rotation was changed in the encoder, extra rotations were included in the ansatz to attempt to see if any pairs seemed optimal, and extra entanglement in the ansatz was attempted at.

For a custom ansatz, we tried a number of patterns, one of which can be seen below.

EthanModel.png

In the end, this resulted in various runs in which we slowly learned which patterns of design worked and which didn't, the result of our several runs. Usually with image training models, there's a steepish drop in the loss, and the accuracy follows after reaching a plateau. However, no matter the tons of variations we tried, we couldn't find any changes which improved the accuracy of our models. We would change a property about our model, then run it a few times, but the average values were still all around the same. An image of our progress in a graph with our submissions can be seen below.

results.png

Overall, it was a great experience getting to meet new people, apply what we know in creative and novel ways, and learn more about this new field!
