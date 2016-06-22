multiverso
==========

Multiverso is a parameter server based framework for training machine learning models on big data with numbers of machines. It is currently a standard C++ library and provides a series of friendly programming interfaces. With such easy-to-use APIs, machine learning researchers and practitioners do not need to worry about the system routine issues such as distributed model storage and operation, inter-process and inter-thread communication, multi-threading management, and so on.
Instead, they are able to focus on the core machine learning logics: data, model, and training.

For more details, please view our website [http://www.dmtk.io](http://www.dmtk.io).

Build
----------

**Linux** (Tested on Ubuntu 12.04)

1. Run ``` mkdir build ```
2. Run ``` cd build ```
3. Run ``` cmake .. ```
4. Run ``` make ```

**Windows**

For windows users, please refer to README in windows folder.


Code of Conduct
----------

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

Related Projects
----------

Current distributed systems based on multiverso:

* [lightlda](https://github.com/Microsoft/lightlda): Scalable, fast, lightweight system for large scale topic modeling
* [distributed_word_embedding](https://github.com/Microsoft/distributed_word_embedding) Distributed system for word embedding
* [distributed_skipgram_mixture](https://github.com/Microsoft/distributed_skipgram_mixture) Distributed skipgram mixture for multi-sense word embedding

