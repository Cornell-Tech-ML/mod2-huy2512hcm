[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/YFgwt0yY)
# MiniTorch Module 2

<img src="https://minitorch.github.io/minitorch.svg" width="50%">


* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module2/module2/

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/operators.py minitorch/module.py minitorch/autodiff.py minitorch/scalar.py minitorch/scalar_functions.py minitorch/module.py project/run_manual.py project/run_scalar.py project/datasets.py

* Below is the training logs and the final images for simple linear dataset that I created:
![alt text](<Screenshot 2024-10-21 at 1.40.30 PM.png>)
![alt text](<Screenshot 2024-10-21 at 1.40.38 PM.png>)
![alt text](<Screenshot 2024-10-21 at 1.40.44 PM.png>)
![alt text](<newplot (7).png>)

* Epoch: 0/500, loss: 0, correct: 0
* Epoch: 10/500, loss: 31.337095698174394, correct: 43
* Epoch: 20/500, loss: 26.008877787474713, correct: 46
* Epoch: 30/500, loss: 18.664009731729752, correct: 47
* Epoch: 40/500, loss: 14.169853456887378, correct: 47
* Epoch: 50/500, loss: 15.006247012242946, correct: 42
* Epoch: 60/500, loss: 8.883912892491072, correct: 49
* Epoch: 70/500, loss: 6.726265078212327, correct: 49
* Epoch: 80/500, loss: 6.068218624303427, correct: 49
* Epoch: 90/500, loss: 5.749453013613978, correct: 49
* Epoch: 100/500, loss: 5.719240457524446, correct: 49
* Epoch: 110/500, loss: 5.346270528111107, correct: 49
* Epoch: 120/500, loss: 4.584908068660921, correct: 49
* Epoch: 130/500, loss: 3.8119356899143906, correct: 49
* Epoch: 140/500, loss: 3.3392056533300187, correct: 49
* Epoch: 150/500, loss: 3.175921273013218, correct: 49
* Epoch: 160/500, loss: 3.316146023510127, correct: 49
* Epoch: 170/500, loss: 5.527208058251281, correct: 48
* Epoch: 180/500, loss: 16.777980763548744, correct: 43
* Epoch: 190/500, loss: 2.744437816296085, correct: 49
* Epoch: 200/500, loss: 2.492578127340595, correct: 50
* Epoch: 210/500, loss: 2.3354511805195726, correct: 50
* Epoch: 220/500, loss: 2.2044140379639363, correct: 50
* Epoch: 230/500, loss: 2.0875629140903027, correct: 50
* Epoch: 240/500, loss: 1.984284211327848, correct: 50
* Epoch: 250/500, loss: 1.8890958020567226, correct: 50
* Epoch: 260/500, loss: 1.802678183375251, correct: 50
* Epoch: 270/500, loss: 1.7229701864373144, correct: 50
* Epoch: 280/500, loss: 1.6491508302788722, correct: 50
* Epoch: 290/500, loss: 1.5805734559903821, correct: 50
* Epoch: 300/500, loss: 1.5166807944590506, correct: 50
* Epoch: 310/500, loss: 1.4570021025536146, correct: 50
* Epoch: 320/500, loss: 1.4011302333054336, correct: 50
* Epoch: 330/500, loss: 1.3487091312053983, correct: 50
* Epoch: 340/500, loss: 1.2994291010739663, correct: 50
* Epoch: 350/500, loss: 1.253020183200957, correct: 50
* Epoch: 360/500, loss: 1.2092431689713368, correct: 50
* Epoch: 370/500, loss: 1.1678987342694038, correct: 50
* Epoch: 380/500, loss: 1.1288566670632985, correct: 50
* Epoch: 390/500, loss: 1.0922534530404135, correct: 50
* Epoch: 400/500, loss: 1.0597451967119218, correct: 50
* Epoch: 410/500, loss: 1.0429640930817528, correct: 50
* Epoch: 420/500, loss: 1.1718332221736518, correct: 50
* Epoch: 430/500, loss: 32.08173787463744, correct: 41
* Epoch: 440/500, loss: 2.9791704418141, correct: 49
* Epoch: 450/500, loss: 1.0696584447991564, correct: 50
* Epoch: 460/500, loss: 1.0120793883614283, correct: 50
* Epoch: 470/500, loss: 0.9780089200539043, correct: 50
* Epoch: 480/500, loss: 0.947185713436845, correct: 50
* Epoch: 490/500, loss: 0.918057871216295, correct: 50
* Epoch: 500/500, loss: 0.8903783215835088, correct: 50




* Below is the training logs and the final images for diagonal dataset that I created:
![alt text](<Screenshot 2024-10-21 at 1.50.19 PM.png>)
![alt text](<Screenshot 2024-10-21 at 1.50.32 PM.png>)
![alt text](<Screenshot 2024-10-21 at 1.50.43 PM.png>)
![alt text](<Screenshot 2024-10-21 at 1.50.55 PM.png>)
![alt text](<Screenshot 2024-10-21 at 1.51.00 PM.png>)
* 
* Epoch: 0/500, loss: 0, correct: 0
* Epoch: 10/500, loss: 20.46267911263876, correct: 43
* Epoch: 20/500, loss: 19.612695497365337, correct: 43
* Epoch: 30/500, loss: 18.470556875573056, correct: 43
* Epoch: 40/500, loss: 17.030876754117617, correct: 43
* Epoch: 50/500, loss: 14.865190078841318, correct: 43
* Epoch: 60/500, loss: 12.309552045264349, correct: 43
* Epoch: 70/500, loss: 10.229861669564757, correct: 43
* Epoch: 80/500, loss: 8.504263487381216, correct: 43
* Epoch: 90/500, loss: 7.128993646099347, correct: 43
* Epoch: 100/500, loss: 5.996109101333122, correct: 48
* Epoch: 110/500, loss: 5.0808152441302425, correct: 49
* Epoch: 120/500, loss: 4.35081690549397, correct: 49
* Epoch: 130/500, loss: 3.7702910728587753, correct: 49
* Epoch: 140/500, loss: 3.309463037688867, correct: 50
* Epoch: 150/500, loss: 2.9487684050873417, correct: 50
* Epoch: 160/500, loss: 2.6594941441778093, correct: 50
* Epoch: 170/500, loss: 2.408798363827443, correct: 50
* Epoch: 180/500, loss: 2.2045713203305155, correct: 50
* Epoch: 190/500, loss: 2.0315122385655493, correct: 50
* Epoch: 200/500, loss: 1.8830369033185463, correct: 50
* Epoch: 210/500, loss: 1.7540799117676569, correct: 50
* Epoch: 220/500, loss: 1.6411355162156407, correct: 50
* Epoch: 230/500, loss: 1.5412282617087363, correct: 50
* Epoch: 240/500, loss: 1.4524206086775386, correct: 50
* Epoch: 250/500, loss: 1.3727528613649593, correct: 50
* Epoch: 260/500, loss: 1.3011083734211297, correct: 50
* Epoch: 270/500, loss: 1.2361508297987016, correct: 50
* Epoch: 280/500, loss: 1.1771251630477573, correct: 50
* Epoch: 290/500, loss: 1.1232236405648874, correct: 50
* Epoch: 300/500, loss: 1.0736649795108175, correct: 50
* Epoch: 310/500, loss: 1.0281296895330878, correct: 50
* Epoch: 320/500, loss: 0.9859968078541852, correct: 50
* Epoch: 330/500, loss: 0.9470186279375683, correct: 50
* Epoch: 340/500, loss: 0.9108404088014004, correct: 50
* Epoch: 350/500, loss: 0.8769828037899611, correct: 50
* Epoch: 360/500, loss: 0.8454542457099645, correct: 50
* Epoch: 370/500, loss: 0.8158793624639203, correct: 50
* Epoch: 380/500, loss: 0.7881775824260429, correct: 50
* Epoch: 390/500, loss: 0.7620878410239716, correct: 50
* Epoch: 400/500, loss: 0.7375526328446345, correct: 50
* Epoch: 410/500, loss: 0.7143724367729625, correct: 50
* Epoch: 420/500, loss: 0.6924756330369284, correct: 50
* Epoch: 430/500, loss: 0.6717631728595631, correct: 50
* Epoch: 440/500, loss: 0.6520785371599157, correct: 50
* Epoch: 450/500, loss: 0.6334299532570874, correct: 50
* Epoch: 460/500, loss: 0.6156681280671966, correct: 50
* Epoch: 470/500, loss: 0.5987926069319363, correct: 50
* Epoch: 480/500, loss: 0.5826839249740098, correct: 50
* Epoch: 490/500, loss: 0.5673428406291561, correct: 50
* Epoch: 500/500, loss: 0.5526675864518412, correct: 50
* 

* Below is the training logs and the final images for split dataset that I created:
![alt text](<Screenshot 2024-10-21 at 2.08.53 PM.png>)
![alt text](<Screenshot 2024-10-21 at 2.08.59 PM.png>)
![alt text](<Screenshot 2024-10-21 at 8.04.16 PM.png>)
![alt text](<Screenshot 2024-10-21 at 8.04.42 PM.png>)

* Epoch: 0/500, loss: 0, correct: 0
* Epoch: 10/500, loss: 33.59838779515852, correct: 16
* Epoch: 20/500, loss: 32.789231439284734, correct: 28
* Epoch: 30/500, loss: 31.792978776763604, correct: 29
* Epoch: 40/500, loss: 30.009638368154054, correct: 33
* Epoch: 50/500, loss: 27.744773546963152, correct: 38
* Epoch: 60/500, loss: 28.779317885133334, correct: 30
* Epoch: 70/500, loss: 26.797656785666167, correct: 31
* Epoch: 80/500, loss: 23.607890820449462, correct: 38
* Epoch: 90/500, loss: 24.133446419470378, correct: 36
* Epoch: 100/500, loss: 20.953817259627638, correct: 39
* Epoch: 110/500, loss: 19.999272011300114, correct: 39
* Epoch: 120/500, loss: 18.192906988243045, correct: 40
* Epoch: 130/500, loss: 15.67458225775635, correct: 40
* Epoch: 140/500, loss: 17.447930397430504, correct: 40
* Epoch: 150/500, loss: 14.838698340641889, correct: 42
* Epoch: 160/500, loss: 13.10573944945098, correct: 42
* Epoch: 170/500, loss: 13.840613859177477, correct: 42
* Epoch: 180/500, loss: 11.595571455971768, correct: 42
* Epoch: 190/500, loss: 11.532251170578043, correct: 42
* Epoch: 200/500, loss: 12.439993691962416, correct: 42
* Epoch: 210/500, loss: 9.518632826857814, correct: 44
* Epoch: 220/500, loss: 7.218623349058216, correct: 47
* Epoch: 230/500, loss: 8.353041275962848, correct: 47
* Epoch: 240/500, loss: 18.532313174931115, correct: 40
* Epoch: 250/500, loss: 6.5064204504849945, correct: 48
* Epoch: 260/500, loss: 4.484859886729247, correct: 49
* Epoch: 270/500, loss: 4.062656455917418, correct: 50
* Epoch: 280/500, loss: 4.488466472842833, correct: 48
* Epoch: 290/500, loss: 13.214544013487814, correct: 44
* Epoch: 300/500, loss: 7.993369361119247, correct: 47
* Epoch: 310/500, loss: 3.9519273704384386, correct: 48
* Epoch: 320/500, loss: 3.4766038397051053, correct: 48
* Epoch: 330/500, loss: 3.7203312168809997, correct: 48
* Epoch: 340/500, loss: 10.497878970179217, correct: 45
* Epoch: 350/500, loss: 6.421779656887044, correct: 47
* Epoch: 360/500, loss: 3.159626199248712, correct: 49
* Epoch: 370/500, loss: 2.836692870906122, correct: 50
* Epoch: 380/500, loss: 2.856356781324173, correct: 49
* Epoch: 390/500, loss: 3.7197325132346544, correct: 48
* Epoch: 400/500, loss: 15.209753108520479, correct: 45
* Epoch: 410/500, loss: 3.5615039054961684, correct: 48
* Epoch: 420/500, loss: 2.542258838808402, correct: 50
* Epoch: 430/500, loss: 2.3262376476836857, correct: 50
* Epoch: 440/500, loss: 2.349175658803714, correct: 50
* Epoch: 450/500, loss: 2.9773463591625595, correct: 48
* Epoch: 460/500, loss: 5.481016267094657, correct: 47
* Epoch: 470/500, loss: 6.444883828479353, correct: 47
* Epoch: 480/500, loss: 2.371435212763499, correct: 49
* Epoch: 490/500, loss: 1.9290630381080915, correct: 50
* Epoch: 500/500, loss: 1.796858746698749, correct: 50


* Below is the training logs and the final images for XOR dataset that I created:
![alt text](<Screenshot 2024-10-21 at 2.23.38 PM.png>)
![alt text](<Screenshot 2024-10-21 at 2.26.59 PM.png>)
![alt text](<Screenshot 2024-10-21 at 8.25.46 PM.png>)
![alt text](<Screenshot 2024-10-21 at 8.27.58 PM.png>)

* Epoch: 0/500, loss: 0, correct: 0
* Epoch: 10/500, loss: 32.54655477856788, correct: 24
* Epoch: 20/500, loss: 26.855572642774334, correct: 40
* Epoch: 30/500, loss: 39.719471609123474, correct: 25
* Epoch: 40/500, loss: 28.52087068677304, correct: 40
* Epoch: 50/500, loss: 26.176676571953923, correct: 35
* Epoch: 60/500, loss: 27.60856900457904, correct: 32
* Epoch: 70/500, loss: 17.87087340668874, correct: 43
* Epoch: 80/500, loss: 20.6028336218841, correct: 38
* Epoch: 90/500, loss: 12.667863952469293, correct: 48
* Epoch: 100/500, loss: 17.670535966683595, correct: 42
* Epoch: 110/500, loss: 16.971676681593205, correct: 43
* Epoch: 120/500, loss: 9.274442543312487, correct: 48
* Epoch: 130/500, loss: 11.899215403868626, correct: 45
* Epoch: 140/500, loss: 14.56432042156211, correct: 43
* Epoch: 150/500, loss: 7.163243204535701, correct: 49
* Epoch: 160/500, loss: 6.403366121758516, correct: 49
* Epoch: 170/500, loss: 43.66438798067526, correct: 35
* Epoch: 180/500, loss: 5.887716226734409, correct: 50
* Epoch: 190/500, loss: 9.257456488271323, correct: 46
* Epoch: 200/500, loss: 6.679137920140885, correct: 48
* Epoch: 210/500, loss: 4.715279750223914, correct: 48
* Epoch: 220/500, loss: 6.1144064193767775, correct: 47
* Epoch: 230/500, loss: 9.11878245989118, correct: 46
* Epoch: 240/500, loss: 4.668244912733726, correct: 48
* Epoch: 250/500, loss: 7.7611490085971475, correct: 46
* Epoch: 260/500, loss: 4.971411647425657, correct: 48
* Epoch: 270/500, loss: 6.668996088149889, correct: 47
* Epoch: 280/500, loss: 5.143235191887949, correct: 47
* Epoch: 290/500, loss: 3.2448068718441725, correct: 49
* Epoch: 300/500, loss: 6.441505886333276, correct: 47
* Epoch: 310/500, loss: 18.609372101095218, correct: 42
* Epoch: 320/500, loss: 3.0538447377818625, correct: 49
* Epoch: 330/500, loss: 3.4038051460697973, correct: 49
* Epoch: 340/500, loss: 29.881413354606156, correct: 33
* Epoch: 350/500, loss: 12.541576254281884, correct: 43
* Epoch: 360/500, loss: 10.556091404838199, correct: 46
* Epoch: 370/500, loss: 14.628849676731937, correct: 44
* Epoch: 380/500, loss: 10.057738549427036, correct: 46
* Epoch: 390/500, loss: 5.194796126934078, correct: 50
* Epoch: 400/500, loss: 5.184104582366782, correct: 49
* Epoch: 410/500, loss: 6.49287662292599, correct: 48
* Epoch: 420/500, loss: 3.808109715600589, correct: 50
* Epoch: 430/500, loss: 3.5543000272474163, correct: 49
* Epoch: 440/500, loss: 8.669135922548428, correct: 47
* Epoch: 450/500, loss: 5.2148156765892795, correct: 48
* Epoch: 460/500, loss: 5.223251578873304, correct: 48
* Epoch: 470/500, loss: 6.656253677832996, correct: 46
* Epoch: 480/500, loss: 5.183581688860073, correct: 46
* Epoch: 490/500, loss: 2.7288479809960076, correct: 50
* Epoch: 500/500, loss: 2.236543018915882, correct: 50