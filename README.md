# SwiftFeather

##### Swift helper framework for https://feathericons.com

## Installation
add `github "tjwio/SwiftFeather"` in `Cartfile`

`carthage update SwiftFeather --platform ios`

## How to Use
`label.font = UIFont.featherFont(size: 17.0)`


`label.text = String.featherIcon(name: .mail)`

or

`label.text = FeatherIcon.mail.rawValue`
