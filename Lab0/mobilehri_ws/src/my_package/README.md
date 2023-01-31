{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Lab 0 26/01/2023"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### List 5 questions you have about ROS following the tutorial, answers you have found and things you still don't get\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "1. Is it possible to have a conflict for the listener, incase there are two nodes publishing topics to it at the same time? [multithreading?] I found a few links online, but I am not fully sure yet."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "2. What will happen if the QoS setting for the publisher and the listener are different? Tried two different times, no change on the output. I thought it was related to duration, but on reading the docs realized that there is a lot more to the profile settings. Not sure what all of it means though."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "3. How come we didn't use the ```rcply.create_node()``` fn? I think this is because we inherited the Node class so the node is getting created in our init fn"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    " 4. What if the same node is ```rclpy.spin()``` twice? As in if two nodes have the same properties? Learnt that each ROS node has to have a unique name. However, an ROS anonymous node is a workaround for this as it adds a unique ID to the name."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "5. How this messaging system will extend to movement in robots? I guess I will find out."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### Feedback on the bootcamp: What was easy and what was difficult to understand?"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "It was easy to follow through. The setup was easy. The analogy for nodes, topics and messages was helpful."
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 2",
   "language": "python",
   "name": "python2"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 2
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython2",
   "version": "2.7.16"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 1
}
