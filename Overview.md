# Neural-Responding-Machine
My project work proposes a text generator, a neural network based generator. I have used various sequence to sequence models like simple RNN, attention RNN and GRU and compared the results based on human evaluation and found that attendance based RNN gives the better result.  In case of simple RNN, it is simply using vanilla RNN to produce a sequence of words as output basically a sentence for the input word. In case of GRU, update and reset gates are applied to the network to forget and learn only the better result and in case of attention RNN, the text generator takes the general encoder-decoder framework, it formalizes the generation of response as a decoding process based on the latent representation of input text. Here both encoding and decoding are realized with recurrent neural networks. RNN’s are able to remember important things about the input they received, which enables them to be very precise in predicting what’s coming next. They can form a much deeper understanding of a sequence and its context, compared to other algorithms. This is the reason why they are the preferred algorithm for sequential data but do not give good results for large amount of data and less accurate. The GRU gives better results for large data. The text generator is trained with data collected from works of Shakespeare.An attentional mechanism has lately been used to improve neural machine translation (NMT) by selectively focusing on parts of the source sentence during translation. All of my three models (Basic_RNN,gru_based_RNN and Attention_RNN) use final.csv vocabulary given. Note: Since all the three models runs on a very small dataset stored in "Sentence.txt" ,very good results are not visible. And i am still working on the Attention_RNN on the implementation side for better results.