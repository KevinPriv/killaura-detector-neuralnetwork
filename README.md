# Minecraft Killaura Neural Anti-Cheat

The Minecraft Killaura Neural Anti-Cheat is a powerful and efficient solution for detecting and combating the Killaura cheat in Minecraft. This system is built using a neural network with an input layer, two hidden layers, and an output layer. It has been trained on the dataset from [HALData](https://github.com/FrozenOrb/HALData).

## Importance of Detecting Killaura

Killaura is a type of cheat used in Minecraft that allows players to automatically attack other players or entities within a certain range and angle, without the need for manual targeting. This cheat gives players an unfair advantage in combat and can ruin the gaming experience for other players on the server. Detecting and preventing Killaura is essential for maintaining a fair and enjoyable environment for all players.

## Results

The accuracy and performance of the anti-cheat system are crucial to ensure both cheater detection and reducing false positives. 

### Accuracy (99%)
Accuracy represents the proportion of correct predictions made by the neural network. A high accuracy indicates that the system can effectively detect Killaura usage while minimizing false positives. This is important because false positives can lead to banning innocent players, causing frustration and a negative experience for legitimate players.

### AUC (99.7%)
AUC (Area Under the Curve) is a metric used to evaluate the performance of a binary classifier. A high AUC score indicates that the neural network is capable of distinguishing between positive (cheating) and negative (non-cheating) instances. This helps ensure that Killaura cheaters are detected while minimizing false positives, maintaining a fair and enjoyable experience for all players on the server.

### Loss (0.0459)
Loss refers to the difference between the predicted values and the actual values. A low loss value indicates that the neural network is performing well in predicting whether a player is using Killaura or not. A lower loss value will help maintain a fair gaming environment by accurately detecting cheaters.

## Credits
Credit goes to FrozenOrb's [dataset](https://github.com/FrozenOrb/HALData) and [concept](https://github.com/FrozenOrb/HAL_Prediction).
