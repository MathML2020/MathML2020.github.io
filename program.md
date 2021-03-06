---
title: "Program"
layout: program
---




# Talks

**NB:** Click title to toggle abstract. 

<sup>*</sup> These sessions will be recorded. We will upload the recorded talks to the LMS youtube channel after the end of this symposium.
<!-- Tab links -->
<div class="tab">
  <!-- <button> </button> -->
  <button class="tablinks" onclick="openDate(event, 'Aug3')" id="defaultOpen">August 3</button>
  <button class="tablinks" onclick="openDate(event, 'Aug4')">August 4</button>
  <button class="tablinks" onclick="openDate(event, 'Aug5')">August 5</button>
  <button class="tablinks" onclick="openDate(event, 'Aug6')">August 6</button>
  <button class="tablinks" onclick="openDate(event, 'Aug7')">August 7</button>
</div>

<!-- Tab content -->
<div id="Aug3" class="tabcontent">
    <table class="tg">
      <tr>
        <th class="tg-lboi" style="min-width:130px">Time (BST)</th>
        <th class="tg-lboi">Event</th>
      </tr>
      <tr>
        <td class="tg-lboi">8:50 - 9:00</td>
          <td class="tg-talk"> Opening remarks by <a href="https://people.bath.ac.uk/jz203/" target="_blank">Johannes Zimmer</a> <a style="color:red"  href= "https://drive.google.com/file/d/1EZjzs9X_GBkubNgDDeQ1gCRiK2Owgm7X/view?usp=sharing" target="_blank">Video</a> </td>
      </tr>
      <tr>
        <td class="tg-lboi">9:00 - 9:45</td>
        <td class="tg-talk"> <details> <summary><a href="https://sites.google.com/site/stephanegchretien/home" target="_blank">Stephane Chretien</a><sup>*</sup>: Understanding interpolation in machine learning. <a style="color:red" href="https://drive.google.com/file/d/1nPj0oHp_kkfruuyGPdxgdf6Xk_2KGZd-/view?usp=sharing" target="_blank">Slides</a> <a style="color:red"  href= "https://drive.google.com/file/d/1lbJbDxaEREsIoRRu-G8ndCaEQk1lL_RE/view?usp=sharing" target="_blank">Video</a>  <br> <small>Chair: Poon</small> </summary><b>Abstract:</b> Recent progress in machine learning practice has lead to the conclusion that over-parametrisation was an essential ingredient in the success of deep neural networks. In this talk, I will survey the recent achievements by many authors from the applied mathematics community for unveiling the reasons why, contrarily to standard belief, overfitting is not the rule when the number of parameters largely exceeds the size of the training set. In particular we will explain the importance of the recently discovered "double descent phenomenon" by Belkin, Hsu, Ma and Mandal. We will end the presentation with a new proposal for studying this intriguing phenomenon and present novel results in this direction obtained jointly with E. Caron in the finite sample and subGaussian setting. </details> </td>
      </tr>
      <tr>
        <td class="tg-lboi">9:45 - 10:30</td>
        <td class="tg-talk"> <details> <summary><a href="https://wwwhome.ewi.utwente.nl/~schmidtaj/" target="_blank">Johannes Schmidt-Hieber</a><sup>*</sup>: Overparametrization and the bias-variance dilemma. <a style="color:red" href="slides/SchmidtHieber.pdf" target="_blank">Slides</a> <a style="color:red"  href= "https://drive.google.com/file/d/1mb8jXl5LpKe2rRGmaRLAhnrXA69bIbY7/view?usp=sharing" target="_blank">Video</a>  <br> <small>Chair:  Poon</small> </summary><b>Abstract:</b> 	For several machine learning methods such as neural networks, good generalisation performance has been reported in the overparametrized regime. In view of the classical bias-variance trade-off, this behaviour is highly counterintuitive. The talk summarizes recent theoretical results on overparametrization and the bias-variance trade-off. This is joint work with Alexis Derumigny. </details> </td>
      </tr>
       <tr>
        <td class="tg-lboi"></td>
        <td class="tg-talk"> Break</td>
      </tr>
      <tr>
        <td class="tg-lboi">13:00 - 13:45</td>
        <td class="tg-talk"> <details> <summary><a href="https://lchizat.github.io/" target="_blank">Lénaïc Chizat</a><sup>*</sup>: Analysis of Gradient Descent on Wide Two-Layer ReLU Neural Networks. <a style="color:red" href="slides/Chizat.pdf" target="_blank">Slides</a> <a style="color:red"  href= "https://drive.google.com/file/d/1dpqzfjEx-Du_kxjnxarZtcemK_sjPirT/view?usp=sharing" target="_blank">Video</a>  <br> <small>Chair: Schmidt-Hieber</small> </summary><b>Abstract:</b> 	In this talk, we propose an analysis of gradient descent on wide two-layer ReLU neural networks that leads to sharp characterizations of the learned predictor and strong generalization performances. The main idea is to study the dynamics when the width of the hidden layer goes to infinity, which is a Wasserstein gradient flow. While this dynamics evolves on a non-convex landscape, we show that its limit is a global minimizer if initialized properly. We also study the "implicit bias" of this algorithm when the objective is the unregularized logistic loss. We finally discuss what these results tell us about the generalization performance. This is based on joint work with Francis Bach.  </details> </td>
      </tr>
      <tr>
        <td class="tg-lboi">13:45 - 14:30</td>
        <td class="tg-talk"> <details> <summary><a href="http://www.cs.ox.ac.uk/people/varun.kanade/myindex.html" target="_blank">Varun Kanade</a>: Implicit Regularization Properties Early-Stopped Gradient-based Algorithms.  <a style="color:red" href="slides/Kanade.pdf" target="_blank">Slides</a>   <br> <small>Chair: Schmidt-Hieber</small>	  </summary><b>Abstract:</b> In this talk, we will discuss implicit regularization properties of gradient-based algorithms. First, we will discuss how gradient descent when applied to unpenalized least squares regression solves the problem of reconstructing a sparse signal from an underdetermined system of linear measurements under the restricted isometry assumption. We present a statitically and computationally optimal algorithm for this problem in this setting and compare the behaviour to the explicit l_1 penalized versions. Next, we will discuss statistical guarantees on excess risk of early-stopped unconstrained mirror descent when applied to the unregularized empirical risk with squared loss on linear models. We will discuss the connection to offset Rademacher complexities and use our method to derive short proofs for new and existing results in the recent literature. This is based on joint work with Patrick Rebeschini and Tomas Vaskevicius. </details> </td>
      </tr>
      <tr>
        <td class="tg-lboi"></td>
        <td class="tg-talk"> Break</td>
      </tr>
      <tr>
        <td class="tg-lboi">15:30 - 16:15</td>
        <td class="tg-talk"> <details> <summary><a href="https://web.math.princeton.edu/~weinan/" target="_blank">Weinan E</a><sup>*</sup>: Machine learning from a continuous viewpoint. <a style="color:red" href="slides/WeinanE.pdf" target="_blank">Slides</a>   <a style="color:red"  href="https://drive.google.com/file/d/1EMdLXJO81D5aTyqnwFwyKMxC8lmr5QC4/view?usp=sharing" target="_blank">Video</a>   <br> <small>Chair: Ehrhardt</small></summary><b>Abstract:</b> Modern machine learning is characterized by two distinctive features: It can be very powerful and it can be quite fragile. The former does not need any elaboration. The latter refers to the fact that the performance of modern machine learning algorithms depends sensitively on the choice of the hyperparameters. This talk centers on continuous formulations of machine learning that are ``well-posed''. We formulate machine learning and the associated optimization process as well-behaved variational and PDE-like problems, and demonstrate that some of the most popular modern machine learning algorithms can be recovered as particular discretizations of these continuous problems. We demonstrate that the performance of the algorithms obtained this way tends to be more robust with the different choices of the hyperparameters. We also discuss how to develop new algorithms under this framework. </details> </td>
      </tr>
      <tr>
        <td class="tg-lboi">16:15 - 17:00</td>
        <td class="tg-talk"> <details> <summary><a href="https://www.ntnu.edu/employees/brynjulf.owren" target="_blank">Brynjulf Owren</a><sup>*</sup>: Structure preservation in (some) deep learning architecture. <a style="color:red" href="slides/Owren.pdf" target="_blank">Slides</a> <a  style="color:red" href="https://drive.google.com/file/d/1qz9J8oVEcz6DeI0HPp0zgmnpLvHfyeAl/view?usp=sharing" target="_blank">Video</a> <br> <small>Chair: Ehrhardt</small> </summary><b>Abstract:</b> 	A deep neural network model consists a large number of layers, each with a number of parameters associated to them. In supervised learning, these parameters are optimised to match training data in the best possible way. The data are propagated through the layers by nonlinear transformations, and in an important subclass of models (ResNet) the transformation can be seen as the numerical flow of a certain type of continuous vector field. Ruthotto and Haber (2017) as well as Cheng et al. have experimented in using different type of vector fields to improve the deep learning model. In particular it is of interest that the trained model has good long time behaviour and are stable in the deep limit, when the number of layers tends to infinity. The models presented in the literature have certain builtin structural properties, they can for instance be gradient flows or Hamiltonian vector fields. A difficulty is however that the models are not autonomous and therefore it is less clear what their flows actually preserve. Starting from such ResNet vector fields, we shall discuss their properties and derive some new nonlinear stability bounds. The long time behaviour of these neural ODE flows is important in the generalisation mode, i.e. after the model has been trained. But also in the training algorithm itself,  structure preserving numerical schemes are important. In deep learning models, the use of gradient flows for optimisation is prevalent, and there exists a number of different algorithms that can be used, some of them can be interpreted as approximations of the flow of certain vector fields with dissipations, such as conformal Hamiltonian systems. If time permits, we will briefly discuss also these algorithms and in particular the need for and efficiency of regularisation. Joint work with: Martin Benning, Elena Celledoni, Matthias Ehrhardt, Christian Etmann, Robert McLachlan, Carola-Bibiane Schönlieb and Ferdia Sherry. </details> </td>
      </tr>
      
    </table>
</div>

<div id="Aug4" class="tabcontent">
    <table class="tg">
    <tr>
        <th class="tg-lboi" style="min-width:130px">Time (BST)</th>
        <th class="tg-lboi">Event</th>
      </tr>
         <tr>
        <td class="tg-lboi">9:00 - 9:45</td>
        <td class="tg-talk"> <details> <summary><a href="http://people.maths.ox.ac.uk/cartis/" target="_blank">Coralia Cartis</a>:   Dimensionality reduction techniques for large-scale optimization problems	<a style="color:red"  href="https://drive.google.com/file/d/1Ghkt6i1ZWOhNWRA7x5mD_mkf--wIdcA1/view?usp=sharing" target="_blank">Video</a>  <br> <small>Chair:  Celledoni</small> </summary><b>Abstract:</b> Known by many names, sketching techniques allow random projections of data from high to low dimensions while preserving pairwise distances. This talks explores ways to use sketching so as to improve the scalability of algorithms for diverse classes of optimization problems and applications, from linear to nonlinear, local to global, derivative-based to derivative-free. Regression problems and Gauss-Newton techniques will receive particular attention. Numerical illustrations on standard optimization test problems as well as on some machine learning set-ups will be presented. This work is joint with Jan Fiala (NAG Ltd), Jaroslav Fowkes (Oxford), Estelle Massart (Oxford and NPL), Adilet Otemissov (Oxford and Turing), Alex Puiu (Oxford), Lindon Roberts (Australian National University, Canberra), Zhen Shao (Oxford).	  </details> </td>
      </tr>
      <tr>
        <td class="tg-lboi">9:45 - 10:30</td>
        <td class="tg-talk"> <details> <summary><a href="https://www.macs.hw.ac.uk/~mp71/about.html" target="_blank">Marcelo Pereyra</a><sup>*</sup>:   Bayesian inference with data-driven image priors: theory, methods, and algorithms	<a style="color:red" href="slides/Pereyra.pdf" target="_blank">Slides</a> <a style="color:red"  href= "https://drive.google.com/file/d/1DB63JoXDpztdw5kqvQJEC7bph8xt8icT/view?usp=sharing" target="_blank">Video</a> <br> <small>Chair: Celledoni</small> </summary><b>Abstract:</b> This talk presents a mathematical and computational methodology for performing Bayesian inference in problems where prior knowledge is available in the form of a training dataset or set of training examples. This prior information is encoded into the model by using a deep neural network, which is combined with an explicit likelihood function by using Bayes' theorem to derive the posterior distribution for the quantities of interest given the available data. Bayesian computation is then performed by using appropriate Markov chain Monte Carlo stochastic algorithms. We study the theoretical properties of the proposed models and computation algorithms and illustrate performance on a range of imaging inverse problems involving point estimation, uncertainty quantification, hypothesis testing, and model misspecification diagnosis. 	  </details> </td>
      </tr>
      <tr>
        <td class="tg-lboi"></td>
        <td class="tg-talk"> Break</td>
      </tr>
      <tr>
        <td class="tg-lboi">13:00 - 13:45</td>
        <td class="tg-talk"> <details> <summary><a href="https://www.ntnu.edu/employees/elena.celledoni" target="_blank">Elena Celledoni</a>:   Deep learning as optimal control and structure preserving deep learning <a href="https://drive.google.com/file/d/1B_omWWOEB6nsobunDotc8AO02NpTQPzg/view?usp=sharing" target="_blank" style="color:red">Slides</a> <br> <small>Chair:  Pereyra</small>  </summary><b>Abstract:</b> There are multiple challenging mathematical problems involved in applying deep learning. We consider recent work by Haber and Ruthotto 2017 and Chang et al. 2018, where deep learning neural networks have been interpreted as discretisations of an optimal control problem subject to an ordinary differential equation constraint. We review the first order conditions for optimality, and the conditions ensuring optimality after discretisation.  There is a growing effort to mathematically understand the structure in existing deep learning methods and to systematically design new deep learning methods to preserve certain types of structure in deep learning. 
We discuss Hamiltonian descent methods. For manifold value data, we present recent work on Riemaniann discrete gradient descent methods on manifolds.
  </details> </td>
      </tr>
      <tr>
        <td class="tg-lboi">13:45 - 14:30</td>
        <td class="tg-talk"> <details> <summary><a href="https://scholar.google.co.uk/citations?user=tV7pohwAAAAJ&hl=en" target="_blank">Pierfrancesco Urbani</a>:   Tracking the dynamics of gradient based algorithms in high dimensional optimization.   <br> <small>Chair:  Pereyra</small>  </summary><b>Abstract:</b> I will discuss how dynamical mean field theory can be employed to track the high dimensional dynamics	  </details> </td>
      </tr>
      <tr>
        <td class="tg-lboi"></td>
        <td class="tg-talk"> Break</td>
      </tr>
      <tr>
        <td class="tg-lboi">15:30 - 16:15</td>
        <td class="tg-talk"><details> <summary><a href="https://www.npl.co.uk/people/spencer-thomas" target="_blank">Spencer Thomas</a><sup>*</sup>:   Metrology and uncertainty in machine learning. <a style="color:red" href="https://drive.google.com/file/d/1ohQLJCqf3ZtheunjK7JSpChVIn7vVM3i/view?usp=sharing" target="_blank">Slides</a>	<a style="color:red"  href= "https://drive.google.com/file/d/1-PECniJJgxxR7PWCRps7mDCefb_kbHTu/view?usp=sharing" target="_blank">Video</a> <br> <small>Chair:  Higham</small>  </summary><b>Abstract:</b> The use and application of machine learning has become common place in many research and industrial domains. The availability of powerful algorithms in a wide range of programming language and implementations has facilitated this, enabling almost anyone to use these tools. However, without sufficient understanding of the models, data, mathematics or statistics, interpretation of outputs from machine learning can be difficult or misleading. The explainability of machine learning is a growing area of research and becoming increasingly important in application areas such as healthcare. Similarly, the challenges of trustworthiness, robustness and uncertainty in machine learning, as well as the data they are tried on, are significant issues in many applications. These align well with metrological concepts of traceability, calibration, uncertainty propagation and standardisation, which can help address these challenges in machine learning. Several areas will be discussed including fundamentals of machine learning and data, and applications to imaging and non-imaging data such as in healthcare domains. 	  </details>  </td>
      </tr>
      <tr>
        <td class="tg-lboi">16:15 - 17:45</td>
        <td class="tg-talk"> <b>Poster session</b>:   Posters 15-26 </td>
      </tr>
      </table>
</div>

<div id="Aug5" class="tabcontent">
    <table class="tg">
    <tr>
        <th class="tg-lboi" style="min-width:130px">Time (BST)</th>
        <th class="tg-lboi">Event</th>
      </tr>
      <tr>
        <td class="tg-lboi">9:00 - 9:45</td>
        <td class="tg-talk"> <details> <summary><a href="https://bispl.weebly.com/professor.html" target="_blank">Jong Chul Ye</a><sup>*</sup>:   Optimal Transport, CycleGAN, Penalized LS: Intertwining Theme for Unsupervised Learning for Inverse Problems. <a style="color:red" href="https://drive.google.com/file/d/1mN2efh05spOJWj8dV73M4hZIC5BMpxcO/view?usp=sharing" target="_blank">Slides</a> <a style="color:red"  href= "https://drive.google.com/file/d/1aDYbVhTghjnMm49jKYcxgOZl7CYeK7EY/view?usp=sharing" target="_blank">Video</a> <br> <small>Chair:  Arridge</small> 	</summary><b>Abstract:</b> The penalized least squares (PLS) is a classic method for inverse problems, where a regularization term is added to stabilize the solution. Optimal transport (OT) is another mathematical framework that has recently received significant attention from the computer vision community, for it provides means to transport one measure to another in an unsupervised manner. The cycle-consistent generative adversarial network (cycleGAN) is a recent extension of GAN to learn target distributions with less mode collapsing behavior. Although similar in that no supervised training is required, the algorithms look different, so the mathematical relationship between these approaches is not clear. In this talk, we provide an important advance to unveil the missing link. Specifically, we propose a novel PLS cost by imposing a deep learning-based inverse path as a regularization term. When used as a transportation cost for optimal transport formulation, this new PLS formulation leads to a novel cycleGAN architecture as a Kantorovich dual OT formulation. One of the most important advantages of this formulation is that depending on the knowledge of the forward problem, distinct variations of cycleGAN architecture can be derived: for example, one with two pairs of generators and discriminators, and the other with only a single pair of generator and discriminator. Experimental results using various inverse problems confirm the efficacy of the proposed method.  	  </details> </td>
      </tr>
      <tr>
        <td class="tg-lboi">9:45 - 10:30</td>
        <td class="tg-talk"> <details> <summary><a href="https://jonasadler.com/" target="_blank">Jonas Adler</a>:   A case for provable properties in neural networks <a style="color:red" href="https://drive.google.com/file/d/138qDo9Eh7vE5_zFtPWJ4VihMMvibWV_Y/view?usp=sharing" target="_blank">Slides</a>  <br> <small>Chair:  Arridge</small> </summary><b>Abstract:</b> Modern deep learning is highly heuristic and theory has either been limited to highly simplified cases or as mere motivations for methods. Provable results that make useful predictions about a trained neural network, a Nyquist theorem for deep learning, seems very far off. In this talk, I'll instead focus on another use of mathematical theory in deep learning which has given several useful tools to engineers: expanding the toolbox of provably correct components in deep learning systems. By far the most useful such component has been backpropagation, but others have been discovered in recent years. I'll try to give an overview, discussing recent discoveries such as invertible networks and spectral normalization, before focusing on some of my recent work in provably correct deep learning accelerated convex optimization.
This is joint work with Sebastian Banert and Jevgenija Rudzusika. 	  </details> </td>
      </tr>
      <tr>
        <td class="tg-lboi"></td>
        <td class="tg-talk"> Break</td>
      </tr>
      <tr>
        <td class="tg-lboi">13:00 - 13:45</td>
        <td class="tg-talk"> <details> <summary><a href="http://www.pc-petersen.eu/" target="_blank">Philipp Petersen</a><sup>*</sup>:   Numerical Solution of Parametric Differential Equations by Deep Neural Networks. <a style="color:red"  href= "https://drive.google.com/file/d/1BJw5ymy8ZYIpTKe8z4wnD-G0-jr_OS_r/view?usp=sharing" target="_blank">Video</a> <br> <small>Chair:  Schönlieb</small>  </summary><b>Abstract:</b> 	We will discuss the application of deep neural networks (DNNs) in numerical analysis. Based on remarkable approximation theoretical results of deep neural networks, in particular, of functions that arise as solutions of elliptic PDEs, it is natural to speculate that DNNs can improve the state of the art of numerical solvers for such problems. Due to the complexity and unreliability of the training of DNNs, this approach is, however, only feasible in special circumstances. An alternative is to train DNNs to approximate the solution map, i.e., the map taking parameters of a PDE to the solution. In this scenario, DNNs can be trained in an expensive offline phase, but the solution of an individual problem can then be computed very efficiently. A drawback of this approach is that the regularity of the solution map is much less understood than the regularities of the solutions of the individual PDEs. In this work, we study the complexity of the solution map through the lens of model order reduction techniques. In this context, we establish theoretical and practical bounds on the approximability of the solution map by DNNs.	  </details> </td>
      </tr>
      <tr>
        <td class="tg-lboi">13:45 - 14:30</td>
        <td class="tg-talk"> <details> <summary><a href="http://www0.cs.ucl.ac.uk/staff/S.Arridge/" target="_blank">Simon Arridge</a><sup>*</sup>:   NonStationary Blind Deconvolution Using Learned Backward Diffusion. <a style="color:red"  href= "https://drive.google.com/file/d/18QmXsh1sUKqMddWXNs-5O18yU5XUf3os/view?usp=sharing" target="_blank">Video</a>	<br> <small>Chair:  Schönlieb</small>   </summary><b>Abstract:</b> It is increasingly recognised that there is a close relationship between some network architectures and iterative solvers for partial differential equations. In this talk we present a network architecture for forward and inverse problems in non-linear diffusion. By design the architecture is non-linear, learning an anisotropic diffusivity function for each layer from the output of the previous layer. The performed updates are explicit, by which we obtain better interpretability and generalisability compared to classical architectures. Since backward diffusion is unstable, a learned regularisation is implicitly learned to stabilise this process. We test results on synthetic image data sets that have undergone edge-preserving diffusion and on experimental data of images view through variable density scattering media. This is joint work with Andreas Hauptmann and Giuseppe di Sciacca. 	  </details> </td>
      </tr>
      <tr>
        <td class="tg-lboi"></td>
        <td class="tg-talk"> Break</td>
      </tr>
      <tr>
        <td class="tg-lboi">15:30 - 16:15</td>
        <td class="tg-talk"> <details> <summary><a href="http://www.alhusseinfawzi.info/" target="_blank">Alhussein Fawzi</a>:   Proving inequalities with deep learning. <a href="https://drive.google.com/file/d/1Kc4fiwlSGRraxR8JeXZaVgxi_MA3CTv4/view?usp=sharing" style="color:red" target="_blank">Slides</a> <a style="color:red"  href= "https://drive.google.com/file/d/1zPIRU07YHD1UX63z6GFmLSngqWIEkMqZ/view?usp=sharing" target="_blank">Video</a> <br> <small>Chair:  Adler</small>  </summary><b>Abstract:</b> I will consider in this talk the fundamental problem of searching for proofs of polynomial inequalities, which has applications in control theory, robotics, geometry, combinatorics, and program verification to name a few. While existing proof systems manipulating polynomial inequalities via elementary inference rules are known to be very powerful, searching for proofs remains a major difficulty. I will introduce a deep reinforcement learning framework to search for a dynamic proof within these proof systems, paying particular attention to incorporating inherent symmetries of the problem as an inductive bias. By comparing our approach with powerful and widely-studied linear programming hierarchies based on static proof systems, I will show that the proposed method reduces the size of the linear program by several orders of magnitude while also improving performance. I will finally conclude with general remarks on the emerging field of using machine learning to solve mathematical problems.	  </details> </td>
      </tr>
      <tr>
        <td class="tg-lboi">16:15 - 17:00</td>
        <td class="tg-talk"> <details> <summary><a href="https://www.damtp.cam.ac.uk/user/cbs31/Home.html" target="_blank">Carola-Bibiane Schönlieb</a><sup>*</sup>: Hybrid mathematical and machine learning methods for solving inverse imaging problems - getting the best from both worlds. <a href="https://drive.google.com/file/d/1zENVdzhagwfnPKC3MUdnbIEWAIgSYHNS/view?usp=sharing" target="_blank" style="color:red">Slides</a> <a style="color:red"  href= "https://drive.google.com/file/d/1ZELzs_AsRdCa8wzPhiO5uBDSMtROKNuY/view?usp=sharing" target="_blank">Video</a> <br> <small>Chair:  Adler</small> 
  </summary><b>Abstract:</b> Inverse problems in imaging range from tomographic reconstruction (CT, MRI, etc) to image deconvolution, segmentation, and classification, just to name a few. In this talk I will discuss approaches to inverse imaging problems which have both a mathematical modelling and a machine learning (data-driven) component. Mathematical modelling is crucial in the presence of ill-posedness, making use of prior information about the imaging data, for narrowing down the search space. Such an approach results in highly generalizable reconstruction and analysis methods which come with desirable solutions guarantees. Machine learning on the other hand is a powerful tool for customising methods to individual data sets. Their combination, getting the best from both of these worlds, is
the topic of this talk, furnished with examples for image classification under minimal supervision with an application to chest x-rays and task adapted tomographic reconstruction.
    </details> </td>
      </tr>
    </table>
</div>

<div id="Aug6" class="tabcontent">
    <table class="tg">
    <tr>
        <th class="tg-lboi" style="min-width:130px">Time (BST)</th>
        <th class="tg-lboi">Event</th>
      </tr>
      <tr>
        <td class="tg-lboi">9:00 - 10:30</td>
        <td class="tg-talk"> <b>Poster session</b>:   Posters 1-14  </td>
      </tr>
      <tr>
        <td class="tg-lboi">10:30 - 11:15</td>
        <td class="tg-talk"> <details> <summary><a href="https://www2.le.ac.uk/departments/mathematics/extranet/staff-material/staff-profiles/it37" target="_blank">Ivan Tyukin</a><sup>*</sup>:   The Riddle of Robustness, Flexibility, and Trustworthiness of Data-driven AI.	 <a href="https://drive.google.com/file/d/1bron3_L1oU0necq9ERXMCScjP4Icf9iF/view?usp=sharing" style="color:red" target="_blank">Slides</a> <a style="color:red"  href= "https://drive.google.com/file/d/1vz33a69jsASZpgpN04DlWr7YL-mjrqfO/view?usp=sharing" target="_blank">Video</a> <br> <small>Chair:  Poon</small>  </summary><b>Abstract:</b> Modern data-driven AI systems show great promise in a host of key areas – from trading and credit scoring to discovery-led science. These systems now outperform humans in Chess and Go and show near-human performance in medical diagnosis, surpassing capabilities of previous-generation algorithms. Decision-making in these new systems is high-dimensional and data- or experience-driven, relying on thousands of variables with mutual dependencies and uncertainties. However, mounting evidence points to that the super-human ability of these AI to learn from huge volumes of data without prior knowledge of data models and distributions make their deductions vulnerable to data inconsistencies, poor data quality, fundamental data uncertainty, and human developers’ bias, leading to poor output integrity and error. In this talk we will discuss a framework enabling high-dimensional data-driven AI to learn on-the-job and correct spurious errors without suffering from the so-called catastrophic forgetting.  We will show that the same framework can be used to develop a formal understanding of fundamental limitations of high-dimensional data-driven AI, including AI brittleness, lack of robustness, and vulnerabilities to adversarial attacks. The new framework enables to produce explainable high-level specifications for the development of new-generation data-driven AI which are robust and resilient “by design”. This, together with the guaranteed capability to learn on-the-job contributes to the concept of provably beneficial AI and ultimately AI trustworthiness. 	  </details> </td>
      </tr>
      <tr>
        <td class="tg-lboi"></td>
        <td class="tg-talk"> Break</td>
      </tr>
      <tr>
        <td class="tg-lboi">13:00 - 13:45</td>
        <td class="tg-talk"> <details> <summary><a href="http://www.damtp.cam.ac.uk/research/afha/anders/" target="_blank">Anders Hansen</a><sup>*</sup>:   On the foundations of computational mathematics, Smale’s 18th problem and the potential limits of AI. <a href="https://drive.google.com/file/d/1SYG5-u0pZMLCKWoIJRfJQhquURCr3pNg/view?usp=sharing" style="color:red" target="_blank" >Slides</a> <a style="color:red"  href= "https://drive.google.com/file/d/17HqRWtywaBqr2h4RyEEzACuVzHHdhDbg/view?usp=sharing" target="_blank">Video</a> <br> <small>Chair:  Tyukin</small>  </summary><b>Abstract:</b> There is a profound optimism on the impact of deep learning (DL) and AI in the sciences with Geoffrey Hinton concluding that 'They should stop educating radiologists now'. However, DL has an Achilles heel: it is universaly unstable so that small changes in the initial data can lead to large errors in the final result. This has been documented in a wide variety of applications. Paradoxically, the existence of stable neural networks for these applications is guaranteed by the celebrated Universal Approximation Theorem, however, the stable neural networks are not computed by the current training approaches. We will address this problem and the potential limitations of AI from a foundations point of view. Indeed, the current situation in AI is comparable to the situation in mathematics in the early 20th century, when David Hilbert’s optimism (typically reflected in his 10th problem) suggested no limitations to what mathematics could prove and no restrictions on what computers could compute. Hilbert’s optimism was turned upside down by Goedel and Turing, who established limitations on what mathematics can prove and which problems computers can solve (however, without limiting the impact of mathematics and computer science).
   We predict a similar outcome for modern AI and DL, where the limitations of AI (the main topic of Smale’s 18th problem) will be established through the foundations of computational mathematics. We sketch the beginning of such a program by demonstrating how there exist neural networks approximating classical mappings in scientific computing, however, no algorithm (even randomised) can compute such a network to even 1-digit accuracy with probability better than 1/2. We will also show how instability is inherit in the methodology of DL demonstrating that there is no easy remedy, given the current methodology. Finally, we will demonstrate basic examples in inverse problems where there exists (untrained) neural networks that can easily compute a solution to the problem, however, the current DL techniques will need 10^80 data points in the training set to get even 1 percent success rate. 	  </details> </td>
      </tr>
      <tr>
        <td class="tg-lboi">13:45 - 14:30</td>
        <td class="tg-talk"> <details> <summary><a href="https://www.microsoft.com/en-us/research/people/awf/" target="_blank">Andrew Fitzgibbon</a><sup>*</sup>:   Counting linear regions in ReLU networks. <a style="color:red">Cancelled</a>	<br> <small>Chair:  Tyukin</small> </summary><b>Abstract:</b> I will talk about recent results in understanding the complexity of deep neural networks.   In particular, it is well known that ReLU networks give rise to piecewise linear functions.  However, a naïve counting of the number of linear regions suggests that the number of regions in a typical deep network will vastly exceed any plausible number of training examples.  Better bounds are emerging, both theoretical and empirical, and I will try to give a summary of results in a way that stimulates further discussion and research.  	  </details></td>
      </tr>
      <tr>
        <td class="tg-lboi"></td>
        <td class="tg-talk"> Break</td>
      </tr>
      <tr>
        <td class="tg-lboi">15:30 - 16:15</td>
        <td class="tg-talk"> <details> <summary><a href="https://users.ece.cmu.edu/~yuejiec/" target="_blank">Yuejie Chi</a><sup>*</sup>:   Fast Global Convergence of Natural Policy Gradient Methods with Entropy Regularization.	<a href="https://drive.google.com/file/d/1PdjQ83v2hqF_MbcrjH6t9poCWIFbxvbr/view?usp=sharing" style="color:red" target="_blank">Slides</a> <a style="color:red"  href= "https://drive.google.com/file/d/1af9P3tet2ZWrPaierzBEzqjU8aJgur4F/view?usp=sharing" target="_blank">Video</a> <br> <small>Chair:  Hansen</small> </summary><b>Abstract:</b> Natural policy gradient (NPG) methods are among the most widely used policy optimization algorithms in contemporary reinforcement learning. This class of methods is often applied in conjunction with entropy regularization --- an algorithmic scheme that helps encourage exploration --- and is closely related to soft policy iteration and trust region policy optimization. Despite the empirical success, the theoretical underpinnings for NPG methods remain severely limited even for the tabular setting. This paper develops {\em non-asymptotic} convergence guarantees for entropy-regularized NPG methods under softmax parameterization, focusing on discounted Markov decision processes (MDPs). Assuming access to exact policy evaluation, we demonstrate that the algorithm converges at least linearly when computing optimal value functions of the regularized MDP. Moreover, the algorithm is provably stable vis-a-vis inexactness of policy evaluation. Our convergence results outperform the ones established for unregularized NPG methods, and shed light upon the role of entropy regularization in accelerating convergence. Joint work with Shicong Cen (CMU), Chen Cheng (Stanford), Yuxin Chen (Princeton), and Yuting Wei (CMU). 	  </details> </td>
      </tr>
      <tr>
        <td class="tg-lboi">16:15 - 17:00</td>
        <td class="tg-talk"> <details> <summary><a href="https://ndrenska.wixsite.com/ver0" target="_blank">Nadia Drenska</a><sup>*</sup>:    A PDE Interpretation of Prediction with Expert Advice. <a href="https://drive.google.com/file/d/1CqdIuAw1bl7WTnyJ-AK-Q95tTWy44UuG/view?usp=sharing" style="color:red" target="_blank">Slides</a> <a style="color:red"  href= "https://drive.google.com/file/d/1w9bPLcxgazafNan9EaRhYifvdB0enKDJ/view?usp=sharing" target="_blank">Video</a> <br> <small>Chair:  Hansen</small> 	 </summary><b>Abstract:</b> Prediction with expert advice is an area of online machine learning, where a player (investor) synthesizes advice from different experts to form predictions. We consider the setting where the environment (market) is adversarial, which results in a repeated two-person game. We are interested in the optimal strategies of the market and the player when the game is played over a long time. We identify PDE continuum limits for this game in the limit of infinite turns; we compute asymptotically optimal strategies for the player and for the environment by using the unique solution to the corresponding nonlinear PDE. This is joint work with Jeff Calder and Robert Kohn.	  </details> </td>
      </tr>
      <tr>
        <td class="tg-lboi"></td>
        <td class="tg-talk"> Break</td>
      </tr>
      <tr>
        <td class="tg-lboi">18:00 - 19:00</td>
        <td class="tg-talk"> <details> <summary><a href="https://www.damtp.cam.ac.uk/user/cbs31/Home.html" target="_blank">Carola-Bibiane Schönlieb (Public lecture)<sup>*</sup></a>:  Looking into the black box: how mathematics can help to turn deep learning inside out. <a style="color:red"  href= "https://drive.google.com/file/d/1pzmkUNzvfprg2Hl_Gq9ZYj5rqwxlLTp3/view?usp=sharing" target="_blank">Video</a> <br> <small>Chair:  Ehrhardt</small>  </summary><b>Abstract:</b> Deep learning has had a transformative impact on a wide range of tasks related to Artificial Intelligence, ranging from computer vision and speech recognition to playing games. Still, the inner workings of deep neural networks are far from clear, and designing and training them is seen as almost a black art. In this talk we will try to open this black box a little bit by using mathematical structure of neural networks described by so-called differential equations and mathematical optimisation. The talk is furnished with several examples in image analysis and computer vision, ranging from biomedical imaging to remote sensing.  </details> </td>
      </tr>
    </table>
</div>

<div id="Aug7" class="tabcontent">
    <table class="tg">
    <tr>
        <th class="tg-lboi" style="min-width:130px">Time (BST)</th>
        <th class="tg-lboi">Event</th>
      </tr>
      <tr>
        <td class="tg-lboi">9:00 - 9:45</td>
        <td class="tg-talk"> <details> <summary><a href="http://kac.maths.ed.ac.uk/~bl" target="_blank">Ben Leimkuhler</a><sup>*</sup>:   Regularizing neural networks using constrained thermodynamic algorithms. <a href="https://drive.google.com/file/d/1pey98lQ8--ynUUEJlYP0IcaQD2NpVwt5/view?usp=sharing" style="color:red" target="_blank">Slides</a> <a style="color:red"  href= "https://drive.google.com/file/d/1y01t_6CwqGF7LKjMU9ePJo8erzlQHWuk/view?usp=sharing" target="_blank">Video</a>  <br> <small>Chair:  Higham</small>  </summary><b>Abstract:</b> 	Large scale neural networks can be trained to 100 percent accuracy on their training set, even for random labels, but such models do not necessarily generalize well to unseen test data. To combat the problem of overfitting, it is common to employ some type of regularization scheme, either explicit penalty terms to control the weights, or implicit approaches such as early stopping or dropout. In this talk I will describe a method for efficiently incorporating algebraic constraints into a stochastic gradient Langevin framework for the training of deep neural networks. Constraints allow direct control of the parameter space of the model and can be used to replace both explicit and implicit regularization strategies. Appropriately designed, they can curb the vanishing/exploding gradient problem and control weight magnitudes and thus stabilize deep neural networks improving the robustness of training algorithms and the consequent generalization capabilities of the trained neural network. I will present examples, discussing both overdamped and underdamped Langevin schemes, distributional convergence issues and numerical discretization methods. The methods are explored in standard test examples from image classification and natural language processing.	  </details> </td>
      </tr>
      <tr>
        <td class="tg-lboi">9:45 - 10:30</td>
        <td class="tg-talk"> <details> <summary><a href="https://www.qmul.ac.uk/maths/profiles/benningmartin.html" target="_blank">Martin Benning</a><sup>*</sup>:   A novel empirical risk minimisation formulation for feed-forward neural networks with non-smooth activations. <a href="https://drive.google.com/file/d/1fQPSbtXvnOcFsr6yUpOtFRgTQRFsLi9o/view?usp=sharing" style="color:red" target="_blank">Slides</a> <a style="color:red"  href= "https://drive.google.com/file/d/1SoEuIlE4lcu72wq0guUWI88vyuq_RzHl/view?usp=sharing" target="_blank">Video</a>	<br> <small>Chair:  Higham</small>   </summary><b>Abstract:</b> In this talk we introduce a novel mathematical formulation for the training of deep neural networks with (potentially non-smooth) proximal maps as activation functions. The advantage of this new formulation is that its partial derivatives with respect to the network’s individual weight- and bias-terms do not require the computation of derivates of the individual activation functions. Instead of estimating the parameters with a subgradient-based optimisation algorithm (as is the state of the art), we therefore use a coordinate descent- or a tailored Bregman alternating direction method of multipliers (BADMM)-approach to train the network parameters; both approaches do not require the computation of subdifferentials of the activation functions. We conclude with preliminary numerical results and discuss potential applications.	  </details> </td>
      </tr>
      <tr>
        <td class="tg-lboi"></td>
        <td class="tg-talk"> Break</td>
      </tr>
      <tr>
        <td class="tg-lboi">13:00 - 13:45</td>
        <td class="tg-talk"> <details> <summary><a href="https://erikbekkers.bitbucket.io" target="_blank">Erik Bekkers</a><sup>*</sup>:   Group Equivariant CNNs beyond Roto-Translations: B-Spline CNNs on Lie Groups. <a style="color:red"  href= "https://drive.google.com/file/d/1eJ4joKkfvLW0vTDSKh-UK-yuv0-xCUPz/view?usp=sharing" target="_blank">Video</a> <br> <small>Chair:  Benning</small> 	 </summary><b>Abstract:</b> Group convolution neural networks (G-CNNs) can be used to improve classical CNNs by equipping them with the geometric structure of groups. Central in the success of G-CNNs is to lift feature maps to higher dimensional disentangled representations in which data characteristics are effectively learned, geometric data-augmentations are made obsolete, and predictable behavior under geometric transformations (equivariance) is guaranteed via group theory. Currently, however, the practical implementations of G-CNNs are limited to either discrete groups (that leave the grid intact) or continuous compact groups such as rotations (that enable the use of Fourier theory). In this talk I lift these limitations and propose a modular framework for the design and implementation of *G-CNNs for arbitrary Lie groups*. In this approach the differential structure of Lie groups is used to expand convolution kernels in a generic basis of B-splines that is defined on the Lie algebra. This leads to a flexible framework that enables *localized*, *atrous*, and *deformable convolutions* in G-CNNs by means of respectively *localized*, *sparse* and *non-uniform* B-spline expansions. The impact and potential of the approach is studied on two benchmark datasets: cancer detection in histopathology slides (PCAM dataset) in which rotation equivariance plays a key role and facial landmark localization (CelebA dataset) in which scale equivariance is important. In both cases, G-CNN architectures out-perform their classical 2D counterparts and the added value atrous and localized group convolutions is studied in detail. 	  </details> </td>
      </tr>
      <tr>
        <td class="tg-lboi">13:45 - 14:30</td>
        <td class="tg-talk"> <details> <summary><a href="https://people.epfl.ch/sofia.olhede?lang=en" target="_blank">Sofia Olhede</a><sup>*</sup>:   Modeling Networks and Network Populations via Graph Distances. <a style="color:red"  href= "https://drive.google.com/file/d/1hBf8yT-6lnFyws6eoUXyIc0pWTN9x2ux/view?usp=sharing" target="_blank">Video</a> <br> <small>Chair:  Benning</small> 	 </summary><b>Abstract:</b> Networks have become a key form of data. Networks allow us to dependence between nodes or actors. Understanding the difference between two networks is also challenging unless they share nodes and are of the same size. We shall discuss how we may compare networks and also consider the regime where more than one network is observed. We shall also discuss how to parametrize a distribution on labelled graphs in terms of a Frechét mean graph (which depends on a user-specified choice of metric or graph distance) and a parameter that controls the concentration of this distribution about its mean. Entropy is the natural parameter for such control, varying from a point mass concentrated on the Frechét mean itself to a uniform distribution over all graphs on a given vertex set. Networks present many new statistical challenges. We shall discuss how to resolve these challenges respecting the fundamental non-Euclidean nature of network observations. This is joint work with Simon Lunagomez (Lancaster University) and Patrick Wolfe (Purdue University) 	  </details> </td>
      </tr>
      <tr>
        <td class="tg-lboi"></td>
        <td class="tg-talk"> Break</td>
      </tr>
      <tr>
        <td class="tg-lboi">15:30 - 16:15</td>
        <td class="tg-talk"> <details> <summary><a href="https://www.maths.ed.ac.uk/~ateckent/" target="_blank">Aretha Teckentrup</a><sup>*</sup>:   Convergence of Gaussian process emulators with estimated hyper-parameters. <a style="color:red" href="https://drive.google.com/file/d/1TO963lh38N_48mJd0O68L-wX8C1fhfV_/view?usp=sharing" target="_blank">Slides</a> <a style="color:red"  href= "https://drive.google.com/file/d/1BGyHEtnBnW7tB8nq_NX-F6GoUPMyqt4J/view?usp=sharing" target="_blank">Video</a> <br> <small>Chair:  Leimkuhler</small>  </summary><b>Abstract:</b> We are interested in the task of estimating an unknown function from data given as a set of point evaluations. In this context, Gaussian process regression is often used as a Bayesian inference procedure, and we are interested in the convergence as the number of data points goes to infinity. Hyper-parameters appearing in the mean and covariance structure of the Gaussian process prior, such as smoothness of the function and typical lenght scales, are often unknown and learnt from the data, along with the posterior mean and covariance. We work in the framework of empirical Bayes, where a point estimate of the hyper-parameters is computed, using the data, and then used within the standard Gaussian process prior to posterior update. Using results from scattered data approximation, we provide a convergence analysis of the method applied to a fixed, unknown function of interest. 	  </details> </td>
      </tr>
      <tr>
        <td class="tg-lboi">16:15 - 17:00</td>
        <td class="tg-talk"> <details> <summary><a href="https://www.research.manchester.ac.uk/portal/matthew.thorpe-2.html" target="_blank">Matthew Thorpe</a><sup>*</sup>:   Rates of Convergence for Cheeger Cuts on Point Clouds. <a href="https://drive.google.com/file/d/15IdApV0Q6XvsrS2gY2i8NQW8OnZ8dyOh/view?usp=sharing" style="color:red" target="_blank">Slides</a> <a style="color:red"  href= "https://drive.google.com/file/d/168aM1KZZT2KYLISAEQxRR2uqD1wI3CX4/view?usp=sharing" target="_blank">Video</a> <br> <small>Chair:  Leimkuhler</small> 	 </summary><b>Abstract:</b> We consider the problem of partitioning an unlabelled data that is represented via a proximity graph. Given a subset of nodes the graph cut is the sum of all edges from the set to its complement. A balanced cut, of which the Cheeger cut is a special case, minimises the ratio of graph cut to a term that penalises small clusters. In this work we make connections between the Cheeger cut on the graph and recent results on the stability of isoperimetric inequalities on manifolds in order to show high probability rates of convergence of the discrete Cheeger cut to its continuum analogue. This work is joint with Nicolas Garcia Trillos (Wisconsin Madison) and Ryan Murray (North Carolina State University). 	  </details> </td>
      </tr>
    </table>
</div>
 



# Posters

The poster session will be held on Gather.Town (a link has been sent out to registered participants). Posters 15-26 will be presented on Tuesday and Posters 1-14  on Thursday, but feel free to enter the poster room anytime to browse. 

Tips for the poster session:
- Please use  Chrome or Firefox.
- Zooming out on your browser will actually make the poster screen larger
- Please mute yourself if you are not speaking.


**Poster Prizes**
We are pleased to announce the following winners of the poster prize:
- First place to  **Allard Hendriksen** for <em>Noise2Inverse: Deep tomographic denoising without high-quality target data</em>
- Second place to  **Salvatore Danilo Riccio**	for	<em>Robustness of Runge-Kutta networks against adversarial attacks</em>
- Third place to **Eliot Ayache and Tanmoy Laskar** for <em>Machine learning applications in High-Energy Time-Domain Astrophysics</em>


| ID | Presenter | Title |
|:---:|:---|:---|
| 001 |  Eliot Ayache / Tanmoy Laskar (University of Bath) |	Machine learning applications in High-Energy Time-Domain Astrophysics  [**Poster**](Posters/Ayache_Eliot.png){:target="_blank"} 	[**Video**](https://drive.google.com/file/d/1Q32LzsS2ct9SmHPQyks4y9QiZgVD-qrD/view?usp=sharing){:target="_blank"} |
| 002 | Pasquale Cascarano (Università di Bologna) |	Deep Plug-and-Play Gradient Method for Super-Resolution   [**Poster**](Posters/Cascarano_Pasquale.png){:target="_blank"}  [**Video**](https://drive.google.com/file/d/1hp7XGSJEheExtvehqRNgrzfjU2EEQslV/view?usp=sharing){:target="_blank"}|
| 003| Eric Baruch Gutierrez Castillo	(University of Bath) | On Primal-Dual Algorithms for Nonsmooth Large-Scale Machine Learning  [**Poster**](Posters/Castillo_Eric.png){:target="_blank"} |
| 004 | Dongdong Chen	(University of Edinburgh) |	Deep Plug-and-Play Network for Compressive MRF reconstruction [**Poster**](Posters/Chen_Dongdong.png){:target="_blank"}  |
| 005 |  | |
| 006 | Jacob Deasy	(University of Cambridge) | 	Closed-form differential entropy of a multi-layer perceptron variant  [**Poster**](Posters/Deasy_Jacob.png){:target="_blank"} |
| 007 | Margaret Duff	(University of Bath) |	Solving Inverse Imaging Problems with Generative Machine Learning Models   [**Poster**](Posters/Duff_Margaret.png){:target="_blank"}  [**Video**](https://drive.google.com/file/d/1pQAGs5dXxJnMdMSF3ZTcR6zvSAcTjTj3/view?usp=sharing){:target="_blank"} |
| 008 | David Fernandes	(University of Bath) |	Unsupervised Learning with GPs and SDEs  [**Poster**](Posters/Fernandes_David.png){:target="_blank"} |
| 009 | Allen Hart	(University of Bath) |	Using Echo State Networks to solve Stochastic Optimal Control Problems   [**Poster**](Posters/Hart_Allen.png){:target="_blank"}   |
| 010 | Allard Hendriksen	(Centrum Wiskunde & Informatica (CWI), Amsterdam) |	Noise2Inverse: Deep tomographic denoising without high-quality target data   [**Poster**](Posters/Hendriksen_Allard.png){:target="_blank"}     |
| 011 | Johannes Hertrich	(TU Berlin) |	Parseval Proximal Neural Networks [**Poster**](Posters/Hertrich_Johannes.png){:target="_blank"} |
| 012 | Nicolas Keriven	(CNRS, GIPSA-lab) |	Universal Invariant and Equivariant Graph Neural Networks  [**Poster**](Posters/Keriven_Nicolas.png){:target="_blank"} |
| 013 | Youngkyu Lee	 (KAIST) |	A parareal neural network emulating parallel-in-time algorithm [**Poster**](Posters/Lee_Youngkyu.png){:target="_blank"}  |
| 014 | Peter Mathé	(Weierstrass Institute) / Abhishake Rastogi (University of Potsdam) |	Inverse learning in Hilbert scales  [**Poster**](Posters/Mathe_Peter.png){:target="_blank"}  |
| 015 | Janith Petangoda	(Imperial College London) |	Transfer Learning: An application of Foliations  [**Poster**](Posters/Petangoda_Janith.png){:target="_blank"} |
| 016 | Gabriele Incorvaia	(University of Manchester)	 |  A deep learning application for Through-the-Wall Radar Imaging  [**Poster**](Posters/Incorvaia_Gabriele.png){:target="_blank"} |
| 017 | Ilan Price (University of Oxford) | Trajectory growth through deep random ReLU networks.   [**Poster**](Posters/Price_Ilan.png){:target="_blank"}   [**Video**](https://drive.google.com/file/d/1K6J7edNr8zlgOXrnsierZQaMIP-kOIek/view?usp=sharing){:target="_blank"}  |
| 018| Abhishake Rastogi	(University of Potsdam) |	Regularization schemes for statistical inverse problems  [**Poster**](Posters/Rastogi_Abhishake.png){:target="_blank"}  |
| 019 | Salvatore Danilo Riccio	(Queen Mary University of London) |	Robustness of Runge-Kutta networks against adversarial attacks  [**Poster**](Posters/DaniloRiccio_Salvatore.png){:target="_blank"}  [**Video**](https://drive.google.com/file/d/10_BuGwbhNcOSxNtpc4z7MExg-OihK79V/view?usp=sharing){:target="_blank"}  |
| 020 | Paul Russell	(University of Bath) |	Learning to solve Rubik’s cube  [**Poster**](Posters/Russell_Paul.png){:target="_blank"} |
| 021| Malena Sabaté Landman	(University of Bath) |	Iteratively Reweighted Flexible Krylov methods for Sparse Reconstruction [**Poster**](Posters/Sabate_Malena.png){:target="_blank"} [**Video**](https://drive.google.com/file/d/1FXWYpcRW9axsPoBZtzzxEMPcqp9_YS6d/view?usp=sharing){:target="_blank"}|
| 022 | Silvester Sabathiel	(NTNU Trondheim) |	A computational model of learning to count in a multimodal, interactive environment.   [**Poster**](Posters/Sabathiel_Silvester.png){:target="_blank"}     [**Video**](https://drive.google.com/file/d/1Mj2kvrgEnb-Lmg8Ew3zbrilfNlqmIWch/view?usp=sharing){:target="_blank"} |
| 023 | Ferdia Sherry	(University of Cambridge) |	Equivariant neural networks for inverse problems in imaging [**Poster**](Posters/Sherry_Ferdia.png){:target="_blank"} |
| 024 | Giuseppe Ughi	(University of Oxford) |	A Model-Based Derivative-Free Approach to Black-Box Adversarial Examples [**Poster**](Posters/Giuseppe_Ughi.png){:target="_blank"}  |
| 025 | Xiaoyu Wang	(University of Cambridge)  |	Gradient-based training of non-smooth neural networks [**Poster**](Posters/Wang_Xiaoyu.png){:target="_blank"}   [**Video**](https://drive.google.com/file/d/1W_WqwP7a4By4XrYx5qGCHyZjzfWAbanY/view?usp=sharing){:target="_blank"}|
| 026 | Kelvin Shuangjian Zhang (ENS Paris) | Wasserstein control of mirror Langevin Monte Carlo   [**Poster**](Posters/Zhang_Kelvin.png){:target="_blank"} |


# Public Lecture

**Speaker:** [Carola-Bibiane Schönlieb](https://www.damtp.cam.ac.uk/user/cbs31/Home.html), Professor at the University of Cambridge.

**Title:** Looking into the black box: how mathematics can help to turn deep learning inside out

**Abstract:** Deep learning has had a transformative impact on a wide range of tasks related to Artificial Intelligence, ranging from computer vision and speech recognition to playing games. Still, the inner workings of deep neural networks are far from clear, and designing and training them is seen as almost a black art. In this talk we will try to open this black box a little bit by using mathematical structure of neural networks described by so-called differential equations and mathematical optimisation. The talk is furnished with several examples in image analysis and computer vision, ranging from biomedical imaging to remote sensing.

**Time:** 18.00 BST, Thursday 6th August 2020.

Sign up [here](https://docs.google.com/forms/d/e/1FAIpQLScuiUa6xDKhjHA1pJcXj-FcC8VihqnHJIYm2UqorWlQ0MC88g/viewform). 
A Zoom link will be sent to registered participants on the day of the lecture.
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		