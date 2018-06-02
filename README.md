# Crabgrass Android Camera Demo

This folder contains an example application utilizing TensorFlow for Android
devices.

## Description

As part of a fun conversation with friends we were discussing gardening and the annoyance of weeding and we pondered whether we could automate the process.

Part one of that would be the programmatic identification of the most common annoyance - crabgrass.

I therefore decided to have some fun and see if such a classifier could be buillt.

I retrained a tensorflow neural net leveraging an existing imagenet model with the last nodes retrained on crabgrass images and loaded the classifier into an example Android app.

The accuracy is not very high at the moment ~50% as I only trained on a couple of hundred images - I will need to collect ~5,000 images to make it feasible.
