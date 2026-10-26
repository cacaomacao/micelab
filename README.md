# micelab

A planned MATLAB project for EEG analysis of mice in an Alzheimer's disease
model. The repository currently contains the MIT license only; no analysis
implementation, example recording, or validated result has been published here.

## First useful milestone

1. Document the recording format, sampling rate, channel layout, units, and
   required MATLAB/toolbox versions.
2. Add one small synthetic recording with a known signal and an explicit expected
   output. Keep animal recordings and identifying metadata outside Git.
3. Implement and test a loader against that fixture before adding preprocessing
   or group comparisons.
4. Record preprocessing choices and produce one reproducible diagnostic figure
   from the synthetic fixture.

The milestone is complete when a fresh checkout can run one documented command
and reproduce that fixture's expected output. Scientific analysis methods and
claims need their own protocol and validation; the project description alone
does not specify them.

## Contribution scope

Prefer small changes with an example input, expected output, MATLAB version,
and exact run command. Keep source code, fixture data, and generated outputs
clearly separated as the implementation is introduced.

## License

See [LICENSE](LICENSE).
