# TLMonthYearPicker
A simple month and year picker for iOS app development.

<p align="center">
 <img src="https://github.com/lee5783/TLMonthYearPicker/raw/master/demo.gif" alt="TLMonthYearPicker"/>
</p>

## How it works

```swift
    self.monthYearPicker.calendar = calendar
    self.monthYearPicker.monthYearPickerMode = .monthAndYear // or '.year'
    self.monthYearPicker.minimumDate = self.minimumDate
    self.monthYearPicker.maximumDate = self.maximumDate
    self.monthYearPicker.delegate = self

    //Picker delegate
    func monthYearPickerView(picker: TLMonthYearPickerView, didSelectDate date: Date) {
        //do your work with selected date object
    }
```

## Add to your project

There are 2 ways you can add TLMonthYearPickerView to your project:

### Manual installation

Simply drag 'TLMonthYearPickerView.swift' into your project.

### Installation with CocoaPods
```ruby
        pod 'TLMonthYearPicker'
```
## License
Usage is provided under the [MIT License](http://opensource.org/licenses/mit-license.php). See LICENSE for the full details.