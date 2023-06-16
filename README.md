# ImageCaptioningUsingTransformers

This is a transformer model created and trained from scratch using TensorFlow. It is trained on the Flickr dataset and can caption images. I have used 2 methods of Tokenization. One is the BERT-based tokenizer and other is tokenization based on occurrence frequency using TensorFlow's TextVectorization layer. Depending on the type of tokenizer, I have created corresponding text encoding layers for positional tokens(PS: Token embedding is always looked up using Tensorflow's Embedding layer whereas the positional encoding method varies). For the BERT-based tokenizer, I have used the trigonometry based approach of positional encoding that was followed in https://github.com/BhavyaShah1234/NeuralMachineTranslationTransformer script and TensorFlow's Neural Machine Translation tutorial . On the other hand, in the frequency based tokenization, I have used TensorFlow's Embedding layer.

Link to BERT-based tokenization approach: https://colab.research.google.com/drive/19x8_WYArGWv39GIAQnP1gryFtATySE5S?usp=sharing
Link to TextVectorization approach: https://colab.research.google.com/drive/1jHsPeBFoDxCNrSliCbReao7M7lkg7mkr?usp=sharing
