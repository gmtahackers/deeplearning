deeplearning
============
We're doing a biweekly study group about **Deep Learning** in Amsterdam: 1 evening (2-3h) every other week. It's for a group of people with strong CS + LA background, pref. some familiarity with machine learning and neural network basics.


Syllabus
--------
| Session  | Date         | Theory                  | Coding                   |
| -------- | ------------ | ----------------------- | ------------------------ |
| *week 1* | *2016-09-18* | *intro talk, NN&DL ch1* | *ch1 coding assignments* |
| *week 2* | *2016-10-02* | *NN&DL^ ch2*            | *webcam demo*            |
| *week 3* | *2016-10-16* | *NN&DL^ ch3*            | *sk-learn neural nets*   |
| *week 4* | *2016-10-30* | *NN&DL^ ch4 + ch5*      | *intro TensorFlow*       |
| *week 5* | *2016-11-13* | *NN&DL^ ch6*            | *TensorFlow (part 2)*    |
| week 6   | 2016-11-27   | papers                  | TensorFlow (projects)    |
| week 7   | 2016-12-11   | papers, projects prgres | TensorFlow (projects)    |
| week 8   | ...          | ...                     | ...                      |
| beyond   | ...          | DL$ ch6, ch9-ch12       | Hinton course (MATLAB)   |

^ [book] Neural Networks and Deep Learning, by Michael Nielsen
$ [book] Deep Learning, by Goodfellow, Bengio and Courville


## Resources
syllabus, proposal: practical approach, but with deep understanding (not just trying github repos): book Nielsen (ML -> DL), then a course (either Google, creative DL, or (outdated) coursera) with corresponding homeworks. Extra: papers (DL classics, microsoft ebook, IBM watson, DeepMind), practical DL projects (TensorFlow, Theano, Torch, Keras.io), deep dreaming, GPU programming

- [book] by Michael Nielsen:
  http://neuralnetworksanddeeplearning.com/chap1.html
- [book] upcoming, view online:
  http://www.deeplearningbook.org
- [course] UvA, Max Welling:
  https://uvadlc.github.io/ in Torch -> also lists 'similar courses'
- [course] by Hinton (2012):
  https://www.coursera.org/course/neuralnets, supposedly outdated algorithms (in apr 2016)
- [course] Deep Learning (TensorFlow, by Google):
  https://www.udacity.com/course/deep-learning--ud730 (part of nanodegree ML)
- [course] Deep Learning & creative applications [2016]:
  https://www.kadenze.com/courses/creative-applications-of-deep-learning-with-tensorflow/info
- [blogpost] Demystifying Deep Reinforcement Learning [2015]:
  https://www.nervanasys.com/demystifying-deep-reinforcement-learning/
- [video lectures] RL Course by David Silver [2015]:
  https://www.youtube.com/watch?v=2pWv7GOvuf0
- [blogpost] Differentiable neural computers [2016]:
  https://deepmind.com/blog/differentiable-neural-computers/
  (With link to paper behind paywall)

## Papers

- how it started: [Hinton 2006](http://www.cs.toronto.edu/~fritz/absps/ncfast.pdf): deep belief networks
- DeepMind & Google papers: [Atari](https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf), [AlphaGo](http://airesearch.com/wp-content/uploads/2016/01/deepmind-mastering-go.pdf), [WaveNet](https://arxiv.org/pdf/1609.03499.pdf)), Building High-level Features Using Large Scale Unsupervised Learning ("Youtube paper"), Vincent Vanhoucke 2012-2015 ("Android papers")
- Watson ([Building Watson](https://www.aaai.org/ojs/index.php/aimagazine/article/download/2303/2165), [many other papers](http://researcher.watson.ibm.com/researcher/view_group_pubs.php?grp=2099)): various techniques combined
- Turing machine (2014 RNN python output predictor, [2014 Neural Turing Machines](https://arxiv.org/pdf/1410.5401v2.pdf))
- more recent: ICCV 2015 CNN examples http://www.computervisionblog.com/2015/12/iccv-2015-twenty-one-hottest-research.html; more examples in these slide decks: SLAM & geometry, Depth vision & geometry, etc
- your favourite paper!


## Software libraries

- theano (Python) paper [4p] http://biglearn.org/2011/files/papers/biglearn2011_submission_18.pdf

- torch (Lua; Facebook/FAIR contribs; used by Google) paper [5p] http://publications.idiap.ch/downloads/reports/2002/rr02-46.pdf

- TensorFlow (python/c++) by Google http://www.tensorflow.org

- Keras.io High-level Python library using theano and tensorflow, also CV

- Caffe http://caffe.berkeleyvision.org/


## Ideas for Projects

- self-learning Mario or Atari games;
  homebrew: https://www.youtube.com/watch?v=qv6UVOQ0F44; DeepMind: https://www.youtube.com/watch?v=V1eYniJ0Rnk, paper https://arxiv.org/pdf/1312.5602v1.pdf
