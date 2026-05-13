Master's thesis project

The project was based on three different approaches to style and artist classification: 

- artist_then_style_fin.ipynb - model that identifies painters and then infers style based on that recognition.
(With a simplification assumed in this project, of each artist belonging to one style only, this problem becomes the
most straightforward, as the model only focuses on recognizing artists)

- style_than_artist_fin.ipybn - model that relies on first identifying the style and then identifying the
painter, but only from ones belonging to the determined style

- dual_remade_fin.ipynb - model simultaneously recognizes both painters and styles and utilizes a loss
function to incorporate both labels

data_prep_fin.ipynb - file containing the code with the data preparation stage, including fragment extraction 
(since the idea of this project was to utilize fragments of paintings for the classification)

A few available sources of paintings were used as a dataset in this project: 
Kaggle dataset (https://www.kaggle.com/datasets/ikarus777/best-artworks-of-all-time), 
Wikiart paintings (https://www.wikiart.org/), 
Wikipedia paintings (https://commons.wikimedia.org/),
museums' online archives (https://www.arthistoryproject.com/about/, https://totallyhistory.com/)
