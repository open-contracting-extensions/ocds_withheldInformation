# Withheld information

Adds an array of `withheldInformation` objects to describe data points that are embargoed or permanently withheld from publication.

## Legal context

In the European Union, this extension's fields correspond to [eForms BG-8 (Not Immediately Published)](https://docs.ted.europa.eu/eforms/latest/reference/business-terms/). For correspondences to eForms fields, see [OCDS for eForms](https://standard.open-contracting.org/profiles/eforms/latest).

## Example

```json
{
  "withheldInformation": [
    {
      "id": "cro-bot-law-18d27a53-0109-4f93-9231-6659d931bce0",
      "field": "cro-bor-law",
      "name": "Cross Border Law",
      "rationale": "Information delayed publication because of ...",
      "rationaleClassification": [
        {
          "scheme": "eu-non-publication-justification",
          "id": "oth-int",
          "description": "Other public interest",
          "uri": "http://publications.europa.eu/resource/authority/non-publication-justification/oth-int"
        }
      ],
      "availabilityDate": "2024-12-31T09:00:00+01:00"
    }
  ]
}
```

## Issues

Report issues for this extension in the [ocds-extensions repository](https://github.com/open-contracting/ocds-extensions/issues), putting the extension's name in the issue's title.
