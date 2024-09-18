# Music-Genre-Classifier
<p>Dataset is taken from <a href="https://www.kaggle.com/datasets/imuhammad/audio-features-and-lyrics-of-spotify-songs/data">kaggle</a>.</p>

<h2>Project files and libraries</h2>
<p>
    <ul>
        <li><code>data/spotify_songs.csv</code> - dataset for model learning;</li>
        <li><code>genre_classification.ipynb</code> - notebook for processing and anylyzing data, search best model;</li>
        <li><code>requirements.txt</code> - txt file with used libraries: <code>numpy</code>, <code>pandas</code>, <code>nltk</code>, <code>scikit-learn</code>, <code>xgboost</code> and etc.</li>
    </ul>
</p>

<h2>Result metrics</h2>
<p>
  Model's achived final metrics:
  <ul>
    <li><code>f1_score(average='macro')</code> = 0.86;</li>
    <li><code>roc_auc_score(average='macro')</code> = 0.98.</li>
  </ul>
</p>
