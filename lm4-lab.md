# LM4 Lab - Get-Date & Get-Member

## Object Type
- System.DateTime

## Three Properties of Interest
1. **DayOfWeek**: Returns the named day of the week for the DateTime instance.
2. **DayOfYear**: Returns the integer day number within the current year.
3. **TimeOfDay**: Returns a TimeSpan representing the time component elapsed since midnight.
# LM4 Lab - PowerShell Objects Investigation

## Task 1: Get-Date
- **Object Type**: System.DateTime
- **3 Properties**:
  - DayOfWeek: Shows what day of the week it is.
  - DayOfYear: Shows what day out of 365 it is.
  - TimeOfDay: Displays the time elapsed since midnight.

## Task 2: Get-Process
- **Object Type**: System.Diagnostics.Process
- **3 Properties**:
  - CPU: Shows how much processor time the process is using.
  - WorkingSet: Shows the memory (RAM) being used.
  - Id: The process ID number.

## Task 3: Get-AzSubscription
- **Object Type**: Microsoft.Azure.Commands.Profile.Models.Core.PSAzureSubscription
- **3 Properties**:
  - Id: Unique ID for the subscription.
  - Name: Display name of the subscription.
  - State: Shows if the subscription is enabled or disabled.

## Task 4: Storing in $subscription
- **Did the object type change?**: No, storing it in a variable didn't change the object type or structure. It's still a PSAzureSubscription object.
- **Useful Property**: TenantId (Shows the Azure AD tenant tied to the account).
