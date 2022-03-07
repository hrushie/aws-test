# Hello World Sample App Pipeline
How to set up dev vs prod deployment -
    
    * For selecting option between two deployment I have added Jenkins parameter called deployment
    * This parameter has two options dev and prod
    * Depends on the deployment it will send it to either rushikesh-dev namespace or rushikesh-prod namespace
    * If we add helm chart file with dev and prod deployment separately it should select deferent environment
    * Currently I have selected only one yaml file as it was instructed to use as default in the instructions
    
Challenges I faced and what I would have added.

    * Primary challenge I faced for using the application was the credentials problem
    * I had never worked with Helm, so it was a good experience to understand the setup and deployment charts.
    * If I had more time, I would have learned helm more deeply to understand to use single chart with dynamic parameterized values for dev vs prod
    * Could have used circle CI but I was comfortable to quickly finish pipeline on Jenkins.
    * I did not implement testing as I could have added a test stage where I can just get the public address with kubectl and verified it with simple curl command

