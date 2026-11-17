# FOCUS Mapping Templates

An open repository of community-contributed mapping files that describe how to convert provider-native billing data into [FOCUS](https://focus.finops.org) (FinOps Open Cost and Usage Specification) format.

## What's in this repository

Each mapping file explains how the columns and values in a provider's native billing export correspond to FOCUS columns. Tools can read these files to perform the conversion automatically, so the same mapping can be reused across tools.

Mapping files live in the [templates](templates/) directory.

## Mapping tool

The FinOps Foundation will host a mapping tool for visualizing and editing mapping files. Link coming soon.

## Disclaimer

Mapping files are contributed by the community and may contain errors or be out of date with provider exports or the FOCUS specification. Review and validate any mapping before relying on its output.

## Contributing

To contribute a new mapping file or a correction, email it to [focus@finops.org](mailto:focus@finops.org) with:

- The provider name
- The billing export or dataset the mapping applies to, including any version information
- The FOCUS version the mapping targets
- Any known limitations or unmapped columns
- A short sample of the native billing data (Optional)

## License

This repository is licensed under the [MIT License](LICENSE).
