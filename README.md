# SpeechAnalyzer
Evaluator of speech quality.

What does this library intend to do?
- Collect labeled data from toastmasters speeches
- Create a model from this labeled data that accepts a new video
- Model outputs the following:
  - Equipment quality (camera resolution)
  - Body language quality
  - Vocal variety quality
  - Specific advice to improve virtual presentations

Once implemented this can be called with:
`/analyze/video/`
