# CVCalendarWithWeekMode

Added additional week mode to CVCalendar which gives an option to switch between 5day view and 7day view

To use this mode, use the added delegate
calendarWeekMode() -> Mode

Sample usage:
func calendarWeekMode() -> Mode {
  return .fiveday
}

Available Modes:
@objc public enum CVCalendarMode: Int {
    case fiveday = 5
    case sevenday = 7
}
