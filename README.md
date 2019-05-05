# tomato_attn

## Spatial Attention Infused Residual CNN for detecting infectious parts of the tomato leaves.

### Highlights
- Novel Attention formulation
- Highest benchmark results on the Plant Village Dataset
- Find publication <a href="https://www.sciencedirect.com/science/article/abs/pii/S1568494619307148">here</a>

Automation in plant disease detection and diagnosis is one of the challenging research areas that has gained significant attention in the agricultural sector. Traditional disease detection methods rely on extracting handcrafted features from the acquired images to identify the type of infection. Also, the performance of these works solely depends on the nature of the handcrafted features selected. This can be addressed by learning the features automatically with the help of Convolutional Neural Networks (CNN). This research presents two different deep architectures for detecting the type of infection in tomato leaves. The first architecture applies residual learning to learn significant features for classification. The second architecture applies attention mechanism on top of the residual deep network. Experiments were conducted using Plant Village Dataset comprising of three diseases namely early blight, late blight, and leaf mold. The proposed work exploited the features learned by the CNN at various processing hierarchy using the attention mechanism and achieved an overall accuracy of 98% on the validation sets in the 5-fold cross-validation.

**Citation**

<cite>Karthik, R., Hariharan, M., Anand, S., Mathikshara, P., Johnson, A., & Menaka, R. (2020). Attention embedded residual CNN for disease detection in tomato leaves. Applied Soft Computing, 86, 105933.</cite>