# My work experience

This section will contain a description of my most interesting experience in the IT. I decided to make a description of my work experience in order not to explain it once again, to remember it and return to it periodically when necessary.


> [!IMPORTANT]
> 1. There will be no examples of the source code, just a general description of what I have done along the way.
> 2. Only the most interesting examples from my practice will be considered.
> 3. The program code of all the tasks I am considering is written by me personally.
> 4. The application's private data is hidden.

The entire description will be presented in English.

***Content***:
1. [LLC "SOKRAT"](https://github.com/DanSoW/my-work-experience?tab=readme-ov-file#llc-sokrat)\
1.1. [Virtualization of tables, drop-down lists and other components.](https://github.com/DanSoW/my-work-experience?tab=readme-ov-file#1-virtualization-of-tables-drop-down-lists-and-other-components)\
1.2. [A component for managing time zones.](https://github.com/DanSoW/my-work-experience?tab=readme-ov-file#2-a-component-for-managing-time-zones)\
1.3. [Transferring information from one object to another.](https://github.com/DanSoW/my-work-experience/tree/main?tab=readme-ov-file#3-transferring-information-from-one-object-to-another)\
1.4. [Custom component for working with date and time.](https://github.com/DanSoW/my-work-experience/tree/main?tab=readme-ov-file#4-custom-component-for-working-with-date-and-time)\
1.5. [System monitoring page](https://github.com/DanSoW/my-work-experience/tree/main?tab=readme-ov-file#5-system-monitoring-page)

# LLC "SOKRAT"

***Location***: Russia, Irkutsk\
***Position:*** Software Engineer\
***Grade***: Middle\
***Work experience***: 2 years\
***What did you do?***: I have been developing a complex, highly loaded and cross-platform web application for managing the "Pritok" security system using React.js and JavaScript.

***Completed tasks***:
1. [Virtualization of tables, drop-down lists and other components.](https://github.com/DanSoW/my-work-experience?tab=readme-ov-file#1-virtualization-of-tables-drop-down-lists-and-other-components)
2. [A component for managing time zones.](https://github.com/DanSoW/my-work-experience?tab=readme-ov-file#2-a-component-for-managing-time-zones)
3. [Transferring information from one object to another.](https://github.com/DanSoW/my-work-experience/tree/main?tab=readme-ov-file#3-transferring-information-from-one-object-to-another)
4. [Custom component for working with date and time.](https://github.com/DanSoW/my-work-experience/tree/main?tab=readme-ov-file#4-custom-component-for-working-with-date-and-time)
5. [System monitoring page](https://github.com/DanSoW/my-work-experience/tree/main?tab=readme-ov-file#5-system-monitoring-page)

## Completed tasks
### 1. Virtualization of tables, drop-down lists and other components. 
[to content](https://github.com/DanSoW/my-work-experience?tab=readme-ov-file#llc-sokrat)

***Description***: A web application very often receives a large number of different data for lists or tables. Their number can reach 30,000, 50,000 or even 100,000 entries and all of them need to be placed on one page without static pagination. Virtualization is perfect for solving this problem. In the process, I got acquainted with the already existing virtualization algorithm and based on it created universal components that are used mostly in a web application.
- [x] **Virtualization of directory tables.**

![virtualize table](https://github.com/DanSoW/my-work-experience/blob/main//images/sokrat/virtual_table_1.png?raw=true)

- [x] **Virtualization of user tables with a large number of records.**

![virtualize table](https://github.com/DanSoW/my-work-experience/blob/main//images/sokrat/virtual_table_2.png?raw=true)

- [x] **Virtualization of a column with components.**

![virtualize table](https://github.com/DanSoW/my-work-experience/blob/main//images/sokrat/virtual_table_4.png?raw=true)

- [x] **Virtualization of the drop-down list.**

*Before*:\
![virtualize table](https://github.com/DanSoW/my-work-experience/blob/main//images/sokrat/virtual_drop_down_1.png?raw=true)

*After*:\
![virtualize table](https://github.com/DanSoW/my-work-experience/blob/main//images/sokrat/virtual_drop_down_2.png?raw=true)

- [x] **Virtualization of components arranged in a single column (comples components)**

![virtualize table](https://github.com/DanSoW/my-work-experience/blob/main//images/sokrat/virtual_column_components.png?raw=true)

### 2. A component for managing time zones. 
[to content](https://github.com/DanSoW/my-work-experience?tab=readme-ov-file#llc-sokrat)

***Description***: During the work, it was necessary to create a mechanism for users that would allow them to manage time zones. Such a mechanism should be flexible and allow you to set multiple time intervals on the same time line. It should also be taken into account that intervals can be combined, copied and moved to adjacent lines. The program code of this component was developed by me on assignment from the organization. This task is one of the most difficult that I have ever solved.

- [x] **Time Zone Editor**

![virtualize table](https://github.com/DanSoW/my-work-experience/blob/main//images/sokrat/time_interval_1.png?raw=true)

- [x] **Managing a single time zone**

![virtualize table](https://github.com/DanSoW/my-work-experience/blob/main//images/sokrat/time_interval_2.png?raw=true)

- [x] **Creating complex time zones (with multiple ranges)**

![virtualize table](https://github.com/DanSoW/my-work-experience/blob/main//images/sokrat/time_interval_3.png?raw=true)

To solve this problem in the Firefox browser, I needed higher mathematics, namely the compilation of the Lagrange polynomial of the 6th order.

For the left indicator time range:
$$f(x) = {-1e}^{-6} * {x}^{6} + {6e}^{-5} * {x}^{5} - 0.0014 * {x}^{4} + 0.0148 * {x}^{3} - 0.0774 * {x}^{2} + 0.6901 * x - 13.901$$

Fot the right indicator time ragne:
$$f(x) = {-9e}^{-7} * {x}^{6} + {6e}^{-5} * {x}^{5} - 0.0013 * {x}^{4} + 0.0139 * {x}^{3} - 0.0729 * {x}^{2} + 0.6818 * x - 0.8993$$

### 3. Transferring information from one object to another.
[to content](https://github.com/DanSoW/my-work-experience?tab=readme-ov-file#llc-sokrat)

***Description***: There are many objects in the system containing information that can be transferred to other objects. This function was implemented by me using the D3.js library, with which I interacted with canvas and rendered the necessary elements. Informagtion is transferred from one object to another, which are connected by a line. The line can be red or blue, depending on whether the transfer of information is successful or not.

- [x] **Transferring information**

![transferring info](https://github.com/DanSoW/my-work-experience/blob/main//images/sokrat/transfer_info_by_object_1.png?raw=true)

- [x] **Example of drawing lines connecting one object to another (dotted line)**

![transferring info](https://github.com/DanSoW/my-work-experience/blob/main//images/sokrat/transfer_info_by_object_2.png?raw=true)

- [x] **Example with device trees**

![transferring info](https://github.com/DanSoW/my-work-experience/blob/main//images/sokrat/transfer_info_by_object_3.png?raw=true)

### 4. Custom component for working with date and time.
[to content](https://github.com/DanSoW/my-work-experience?tab=readme-ov-file#llc-sokrat)

***Description***: The existing date and time component had a number of flaws that needed to be fixed. I have developed a new component for working with date and time, which is displayed the same way in different browsers. The component works the same as the standard date and time component in the Chrome browser.

- [x] **Datetime component**

![datetime component](https://github.com/DanSoW/my-work-experience/blob/main//images/sokrat/custom_datetime_component_1.png?raw=true)

- [x] **Displaying multiple dates**

![datetime component](https://github.com/DanSoW/my-work-experience/blob/main//images/sokrat/custom_datetime_component_2.png?raw=true)

- [x] **Displaying the calendar in Firefox**

![datetime component](https://github.com/DanSoW/my-work-experience/blob/main//images/sokrat/custom_datetime_component_3.png?raw=true)

### 5. System monitoring page.
[to content](https://github.com/DanSoW/my-work-experience?tab=readme-ov-file#llc-sokrat)

***Description***: There are many components in the system that need to be constantly monitored. This page contains all the most important components of the system, the state of which must be constanlty checked or performed any tasks with them.

- [x] **General system status page**

![datetime component](https://github.com/DanSoW/my-work-experience/blob/main//images/sokrat/status_system_1.png?raw=true)

- [x] **System features**

![datetime component](https://github.com/DanSoW/my-work-experience/blob/main//images/sokrat/status_system_2.png?raw=true)

- [x] **Detailed information about the possibilities**

![datetime component](https://github.com/DanSoW/my-work-experience/blob/main//images/sokrat/status_system_3.png?raw=true)

- [x] **Performing replicator tasks in real time**

![datetime component](https://github.com/DanSoW/my-work-experience/blob/main//images/sokrat/status_system_4.png?raw=true)

![datetime component](https://github.com/DanSoW/my-work-experience/blob/main//images/sokrat/status_system_5.png?raw=true)