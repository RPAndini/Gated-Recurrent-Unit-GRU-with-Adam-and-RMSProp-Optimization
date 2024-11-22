# Gated-Recurrent-Unit-GRU-with-Adam-and-RMSProp-Optimization

<h1> GATED RECURRENT UNIT </h1>

  Gated Recurrent Unit (GRU) is an algorithm developed from the Recurrent Neural Network (RNN). GRU was first introduced in 2014 by Kyunghyun Cho et al. with the goal of addressing the vanishing gradient problem commonly encountered in RNNs (Chung, et al., 2014). The vanishing gradient problem occurs when the gradients produced by the activation function become very small or even vanish during the training of a neural network model, especially in recurrent neural networks (RNNs) (Bengio, et al., 1994). This can make it difficult to understand and learn long-term dependencies in sequential data or time series. Small gradients make it hard for the network to transmit information from earlier timesteps, as they do not provide a strong enough signal to generate significant weight updates. GRU is one of the architectures designed to solve this problem by utilizing gating mechanisms (Googfellow, et al., 2016).

The GRU architecture is similar to Long Short-Term Memory (LSTM) but has a simpler structure because it does not require a separate memory cell unit to store information (Chung, et al., 2014). There are two gates in GRU to control the flow of information: the update gate and the reset gate. The update gate determines how much information from previous timesteps should be retained and used as input for the next timesteps. Meanwhile, the reset gate functions to decide which information should be reset or discarded from previous timesteps (Cho, et al., 2014). The following is an illustration of the GRU architecture.

![image](https://github.com/user-attachments/assets/c432931d-e3f1-46d1-875f-4f79103ebd60)


<h3>Update Gate</h3>
The update gate is a mechanism that helps the model determine how much information from the past (previous timesteps) is retained and used to generate output in subsequent timesteps (Kostadinov, 2017). The update gate is formulated in the following equation:

𝒛𝒕 = 𝜎(𝑾𝒛𝒙𝒕 + 𝑼𝒛𝒉𝒕−𝟏 + 𝒃𝒛)


<h3>Reset Gate</h3>
The reset gate is a mechanism used to determine how much information from previous timesteps should be erased or forgotten (Kostadinov, 2017).

<h3>Candidate Hidden State</h3>

<h3>Hidden State</h3>
