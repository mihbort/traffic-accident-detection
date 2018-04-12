# traffic-accident-detection
Naive approach based on car track analysis

### Pipeline
1. Preproces:
    - Convert to Gray
    - Downscale
    - Blur
2. BGS using GMM
3. Find moving objects and track
4. Extract movement features
5. Classify them
