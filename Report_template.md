---
pdf_options:
    format: a4
    margin: 40mm 40mm
    printBackground: true
    body_class: markdown-body
    css: |-
        .markdown-body { 
            font-family: ubuntu mono, sans-serif;
            font-size: 11px;
        }
    headerTemplate: |-
        <style>
            section {
                margin: 20mm auto;
                font-family: ubuntu mono, sans-serif;
                font-size: 11px;
            }
        </style>
    footerTemplate: |-
        <section>
            <div>
                <span class="pageNumber"></span>
            </div>
        </section>
---

# <PROTOCOL_NAME> Audit

<DATE>

Audited by: [Arvolear](https://x.com/Arvolear).

## Disclaimer

A smart contract audit does not guarantee absence of bugs, vulnerabilities, and exploits. Subsequent audits and bug bounties are highly recommended.

## About <PROTOCOL_NAME>

> Brief description of the protocol, architectural aspects, test coverage, and documentation.

## Audit Summary

> Few sentences about the protocol's safety, the number of **critical** and **high** vulnerabilities

## Severity classification

- Optimization - The issue suggests how to optimize a smart contract.
- Note​ ​- The issue requires attention, yet does not pose any risks.
- Low​ - The issue has minimal impact on the contract’s ability to operate.
- Medium​ - The issue affects the contract's operability and does not lead to a loss of funds.
- High​ - The issue leads to a loss or incorrect allocation of funds.
- Critical​ - The issue leads to a straightforward exploit.

## Analysis Summary

Review commit hash - `commit hash`

Fixes review commit hash - `commit hash`

### Scope

Smart contracts in scope of the audit:

- `path-to-smart-contract`
- `path-to-smart-contract`

Number of issues found, categorized by their severity:

- Critical: x issues
- High: x issues
- Medium: x issues
- Low: x issues
- Note: x issues
- Optimization: x issues

## Findings

### [C-01] "Severity" - "Issue title"

#### Description

> Finding description

#### Recommendation

> Finding recommendation

#### Client comments

> Finding comments
