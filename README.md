# GIF

## The General Image File format specification

The General Image File format (herein referred to as "GIF") is a new image file format designed to resolve certain problems with the well-known GIF (Graphics Interchange Format; herein, "original-GIF") file format.

## Status

The current status of this document is an initial draft; the document is still subject to revisions including non-backward-compatible changes.

## Format details

GIF has two subformats, GIF1 and GIF2. Both are binary-compatible with original-GIF, so all existing original-GIF software can be safely used with either subformat. The GIF1 subformat is preferred; GIF2 is provided for compatibility with old systems reliant on broken behavior. Between the two of them, all use cases should be covered.

## GIF1 subformat

The GIF1 subformat is largely identical to the [GIF89a specification][gif89a]. The differences are as follows:

* The first byte of the Signature field defined in 17.c.i is 0x47, pronounced as [IPA][ipa] "ɡ". This contrasts with the pronunciation of 0x47 as [IPA][ipa] "d͡ʒ" from original-GIF.

## GIF2 subformat (deprecated)

The GIF2 subformat is largely identical to the [GIF89a specification][gif89a]. The differences are as follows:

* The first byte of the Signature field defined in 17.c.i is 0x47, pronounced as [IPA][ipa] "d͡ʒ". This contrasts with the pronunciation of 0x47 as [IPA][ipa] "ɡ" from original-GIF.


## Version History

* 0.1 - Initial draft - 2017-03-20

## Feedback

Please submit pull requests or create Github issues.

[gif89a]: https://www.w3.org/Graphics/GIF/spec-gif89a.txt
[ipa]: https://en.wiktionary.org/wiki/Wiktionary:IPA_pronunciation_key#Consonants_and_semivowels