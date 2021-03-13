# Master-Thesis

The Thesis is concerned with dealing with user preference uncertainty in Automated Negotiation. A priori, the user's preferences are unkown to the representative agent. They are modeled by a utility function with finitely many parameters. The agent is allowed to query the user on his/her utility at a cost. The question we ask is the following: \textit{How do we query the user optimally to estimate the utility?} 

This project is the agent implementation of an application to the framework presented in the thesis. We work with Linear Additive utilities \(u:[L_1,H_1]\times\cdots\times[L_n,H_n]\to[0,1]\) where $u(\omega) = \sum_{i=1}^n \theta_i\cdot u_i(\omega_i)$ and $$u_i$$'s are continuous monotone and known to the agent. We can query the user with questions $(\omega\leq \omega')?$. Details of the optimal query sequence can be found in the thesis and in the code of the main notebook.
