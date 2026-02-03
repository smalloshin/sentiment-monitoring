# China-Philippines Diplomatic Sentiment Monitoring: Policy Evolution 2005-2024

An interactive immersive article analyzing China-Philippines diplomatic relations through LLM-enhanced sentiment analysis of official discourse.

## Overview

This project presents a sentiment monitoring system that quantifies policy changes through automated analysis of official Chinese media coverage of the Philippines. The system evaluates eight dimensions of diplomatic sentiment and identifies structural turning points where policy undergoes fundamental shifts.

## Key Features

- **Interactive Time Series Chart** - Track coerciveness scores with political event markers (2012 Scarborough Shoal, 2016 Duterte Pivot, 2021 Structural Breakpoint)
- **Inverse Relationship Visualization** - Explore how coerciveness and cooperation scores move in opposite directions
- **Radar Chart with Year Selector** - Compare all eight dimensions across different time periods
- **Sentence Search and Scoring** - Explore individual sentences with detailed dimension-by-dimension analysis

## Eight Dimensions of Analysis

1. **Coerciveness** - Extent of coercive measures and threats
2. **Assertiveness** - Strength of policy stance and principle assertion
3. **Great Power Competition** - Framing within US-China strategic rivalry
4. **Cooperation** - Emphasis on bilateral cooperation and mutual benefit
5. **Nationalism** - Nationalist rhetoric and sovereignty emphasis
6. **National Interest** - Framing around Chinese national interests
7. **Relative Power** - References to power dynamics and capabilities
8. **Other** - Additional relevant dimensions

## Historical Periods

- **2005-2011**: Relative Stability
- **2012**: Scarborough Shoal Incident (First Turning Point)
- **2013-2015**: Island-Building Campaign
- **2016**: Arbitration & Duterte Pivot (Second Turning Point)
- **2017-2020**: "Honeymoon Period"
- **2021**: Structural Breakpoint (Bai-Perron)
- **2022-2024**: Marcos Administration & High Confrontation

## Key Findings

1. **2012 Scarborough Shoal Incident** - Coerciveness jumps from 0.35 to 0.62 (+77%)
2. **2016 Duterte Pivot** - Coerciveness drops to 0.38 (-38%), cooperation rises to 0.72 (+227%)
3. **2021 Structural Breakpoint** - Statistically significant shift in baseline coerciveness levels
4. **2024 Great Power Competition** - Great power competition score reaches 0.62, indicating strategic rivalry framing

## Methodology

The system consists of six components:
1. Data Ingestion (People's Daily Archives)
2. Keyword Filtering (Philippines-related content)
3. Sentence Segmentation (NLP-based)
4. Prompt Design (8 dimension-specific prompts)
5. LLM Inference (Large Language Model scoring)
6. Statistical Analysis (Bai-Perron Breakpoint Test)

## Usage

Open `index_template.html` in a web browser to interact with the immersive article. All visualizations are fully interactive and include educational guidance.

## Technical Stack

- HTML5
- JavaScript (Plotly.js for interactive charts)
- CSS3

## Limitations

- Data limited to People's Daily (official government position)
- LLM scoring based on model interpretation
- Annual aggregation may obscure monthly/quarterly fluctuations
- Correlation does not imply causation
- Historical patterns do not guarantee future repetition

## References

- Bai, J., & Perron, P. (1998). Estimating and testing linear models with multiple structural changes.
- Callahan, W. A. (2016). China's "Asia Dream": The Belt and Road Initiative and the new regional order.
- Fravel, M. T. (2011). Strong borders, secure nation: Cooperation and conflict in China's territorial disputes.
- Liff, A. P., & Ikenberry, G. J. (2014). Racing toward tragedy? China, Russia, and the competition for the Asia-Pacific.
- Storey, I. (2016). Southeast Asia and the rise of China: The search for security.
- Thayer, C. A. (2018). The South China Sea dispute: Navigating the geopolitical minefield.

## License

This work is provided for academic and research purposes.

## Contact

For questions or feedback, please open an issue on GitHub.
