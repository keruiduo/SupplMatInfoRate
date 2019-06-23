# Supplementary Information for the paper "Different languages, similar encoding efficiency: comparable information rates across the human communicative niche"

These supplementary materials contain:

  - the primary data as two TAB-separated CSV files:
    - `InfoRateData.csv`: contains most of the primary data as follows:
      - **Speaker**: the unique speaker IDs
      - **Language**: the language code
      - **Text**: the text ID
      - **Sex**: the speaker's sex (*F*=female, *M*=male)
      - **Duration**: the text's duration (in seconds)
      - **NS**: the text's canonical number of syllables
      - **ShE**: the language's Shannon Entropy
      - **ID**: the language's Information Density
      - **Age**: the speaker's age (in years)
    - `AutomaticSylDetect.csv`: contains the results of the automatic syllable detection algorithm, as follows:
      - **soundname**: the unique identifier of the soundfile (= a text produced by a given speaker in a given language)
      - **nsyll**: the detected number of syllables
      - **npause**: the number of detected pauses (longer than 150ms)
      - **dur**: the total duration (in seconds)
      - **phonationtime**: the duration of the actual phonation (in seconds)
  - the full Rmarkdown analysis and plotting script `InfoRate.Rmd`
  - the resulting HTML output `InfoRate.html`
