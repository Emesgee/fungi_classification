# fungi_classification
Fungi classification in pytorch focusing on image data pipeline



<p><h2>
    In this turorial I am going to classify different types of champignon.
</h2></p><br>
<b>Dataset pipeline is as follows:</b><br><br>
<li>1: finding the champignon types and downloading 100 images of each type is its own folder</li>
<li>2: creating data.json file where each id and label is stored</li>
<li>3: deleting all png files and resizing all pictures to (200 x 200)</li>
<li>4: create a test, train and validation datasets variables</li><br>
<b style ='color:red'>step 3 and 4 will be repeated to ceate (300 X 500) and (600 x 800). This way we have more data in our data set and the prediction in my understanding becomes more accurate</b></p><br>
