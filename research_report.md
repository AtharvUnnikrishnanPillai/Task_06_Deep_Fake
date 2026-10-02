# Task 6 Research Report

Author: Atharv Unnikrishnan Pillai

## Purpose

I generated two synthetic audio recordings using ElevenLabs and supplied an AI-detection screenshot to evaluate how synthetic speech can be produced and identified.

The recordings are the primary artifacts for this assessment. The analysis distinguishes technical observations from subjective judgments and avoids treating a detector score as proof of general accuracy.

## Production Evidence

Both original filenames identify ElevenLabs and the voice “Roger — Laid-Back, Casual, Resonant.”

The first filename contains the export identifier 00_27_09, while the second contains 00_30_46. These identifiers distinguish the files; their timezone and exact generation times have not been independently verified.

The filenames also contain the string pre_sp100_s50_sb75_v4. This string is preserved as filename evidence, but it is not treated as a verified record of model settings.

The exact scripts, selected model, interface settings, account tier, and resource use still need to be recorded.

## Technical Comparison

| Characteristic | Recording 01 | Recording 02 |
|---|---:|---:|
| Duration | 55.875875 seconds | 58.122438 seconds |
| File size | 910,662 bytes | 946,607 bytes |
| Format | MP3 | MP3 |
| Sample rate | 44,100 Hz | 44,100 Hz |
| Channels | Mono | Mono |
| Nominal audio bitrate | 128 kbps | 128 kbps |
| Decode errors reported | None | None |

The second recording is approximately 2.25 seconds longer.

This difference does not establish what changed during generation. It could reflect differences in text, pacing, pauses, or other factors. A causal explanation requires the actual generation record.

Both recordings meet the assignment’s approximate duration target.

## Iteration

The two files demonstrate that two outputs were produced. However, the assignment requires distinct approaches or substantial changes in prompts, settings, or pipelines.

The specific difference between these attempts must be documented before describing them as two distinct approaches.

No particular change in speed, stability, expressiveness, or source text is inferred from the filenames alone.

## AI Detection Results

The supplied screenshot reports an AI score of 95%, a maximum score of 98%, and an average score of 95%.

All 10 analyzed segments are labeled AI Generated. No segments are assigned to Likely AI, Likely Human, or Human.

The first three fully visible segment scores are:

- 00:00–00:06: 94%
- 00:06–00:12: 96%
- 00:12–00:18: 96%

The screenshot’s displayed duration and size match recording 02. Because its filename is truncated and no file hash is shown, identifying recording 02 as the tested file remains an inference.

No separate detection result was supplied for recording 01.

## Interpretation

The detector’s classification agrees with my report that the audio was generated using AI.

However, the displayed 95% score should not be interpreted as a measured accuracy rate or a validated probability.

This experiment contains no human-recorded control, no false-positive test, and no comparison across detectors. Ten segments from a single recording are not ten independent test recordings.

The screenshot gives a general explanation referring to known AI voice-synthesis patterns. It does not expose enough methodological detail to independently audit the result.

## Audio Quality Evaluation

Technical inspection confirmed successful decoding. It did not establish naturalness, clarity, emotional realism, or accurate pronunciation.

A complete listening evaluation should compare:

- Pronunciation of names and technical terms.
- Delivery of numerical values.
- Pauses and transitions.
- Cadence and emphasis.
- Audible artifacts.
- Whether the narration sounds synthetic without prior knowledge.

No new preference or timestamped listening observations have been supplied for this pair of recordings.

Earlier feedback about a clearer “second version” concerned a previous audio comparison and is not treated as a review of these ElevenLabs recordings.

## Disclosure and Provenance

The published filenames begin with AI_generated, and the README identifies the recordings as synthetic.

The audio copies have not been edited to insert a spoken disclosure. Any disclosure already present must be checked in the final recordings.

The inspected MP3 metadata includes an encoder tag. That tag does not authenticate authorship, consent, or the generating model.

No signed content-credential validation or watermark-survival test was performed on these recordings.

The voice label in an export filename is not itself a license record. Applicable usage rights should be retained with the production documentation.

## Findings

The available evidence supports three conclusions:

1. Both recordings are technically readable MP3 files within the assignment’s duration target.
2. The supplied detector labels the likely second recording as AI-generated.
3. The detector result does not establish factual correctness, permission, listener deception, or general detection reliability.

## Remaining Documentation

Before final submission, add:

- Exact source scripts.
- The change between the two attempts.
- Verified model and generation settings.
- Account limits and actual resource use.
- Actual time spent.
- Detector name or website.
- Confirmation of which file was tested.
- Listening observations for each recording.
- Confirmation of spoken disclosure.

No missing settings, failed attempts, working hours, or personal reactions have been invented.
