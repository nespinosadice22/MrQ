To get up env up and running: 
1. python -m venv venv (only once)
2. source venv/bin/activate (run this to reactivate anytime)
3. pip install -r requirements.txt (only once)
4. pip install "gym[classic_control]" (only once)

Venv/ is in our .gitignore file because it's huge, so it won't push to git.  

To try out an environment: 
1. cd MRQ
2. python main.py 
    --env [your env here] 
    --seed [pick a seed here, can then look at results to compare] 
    --total_timesteps [# timesteps here, say 20k]
    --device cpu 

    See main for more but those are the basic ones for now 


