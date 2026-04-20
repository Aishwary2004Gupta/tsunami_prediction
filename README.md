# tsunami_prediction

Natural disasters have always been one of the most dangerous things for people and society. Tsunamis are thought to be the most dangerous of all these disasters because they hit coastal areas very quickly and don't give people much time to get away. The 2004 Indian Ocean tsunami killed more than 227,000 people in fourteen countries. 

The 2011 tsunami in Japan not only destroyed whole coastal towns but also caused a serious nuclear accident. These two events made it clear that the current warning systems aren't good enough and that we need better and faster ways to make predictions.

Underwater earthquakes are the main cause of most tsunamis. Tsunami waves happen when tectonic plates move quickly along their edges under the ocean. This shakes up the water above them. This connection means that information about earthquakes, such as their size, depth, and location, can help us guess whether a tsunami will happen or not. Most traditional methods for predicting tsunamis rely on complicated wave simulation models that need a lot of computing power and real-time ocean data that isn't always available. So there is a clear reason to try machine learning methods that can work directly from earthquake parameters and make predictions faster.

You can teach machine learning models which earthquakes caused tsunamis and which did not by using records of past earthquakes. But there is one big problem with this method: tsunamis don't happen very often. When you look at a lot of earthquake data over a long period of time, there are very few earthquakes that actually caused a tsunami. This leads to a problem known as class imbalance. When a model is trained on data that is not balanced, it tends to predict that everything is not a tsunami because that is the most accurate way to do it. But this is totally wrong for a warning system where missing even one real tsunami event can kill thousands of people.

<img width="770" height="469" alt="image" src="https://github.com/user-attachments/assets/b9f94c80-7730-43a7-a069-55deb12e345a" />
