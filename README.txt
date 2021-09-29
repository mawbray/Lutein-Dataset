# Input-Output data used to construct a dynamical model of a lutein photo-production paper
- associated with the paper https://arxiv.org/abs/2104.11706
Repo details a h5py file with dictionary of data saved as: 'model_dict':{'x': xin, 'y': y, 'u':u_t}
  where x,y denote input and output states (i.e. state at t and t+1 respectively) and u denotes the associated control input (at time t)
  inputs to a model of this dynamical system are then x and u, with outputs defined by y
