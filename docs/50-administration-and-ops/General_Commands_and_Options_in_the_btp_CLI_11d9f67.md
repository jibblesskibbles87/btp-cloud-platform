<!-- loio11d9f67d2c68485ca2f435b955d3b85b -->

# General Commands and Options in the btp CLI

Learn how to work with the SAP BTP command line interface \(btp CLI\). For example, how to log in, get help, and set a default context for commands.



<a name="loio11d9f67d2c68485ca2f435b955d3b85b__section_dw1_wg3_xkb"/>

## General Commands

```
`btp login`
```

```
`btp logout`
```

```
`btp target`
```



<a name="loio11d9f67d2c68485ca2f435b955d3b85b__section_pdm_xg3_xkb"/>

## General Options for Each Command

The following options are available for each command. They need to be typed right after the base call `btp`, and they can be combined \(for example, `btp --verbose --help list accounts/subaccount`. The `--help` option also works at the end of a command call.


<table>
<tr>
<th valign="top">

Options



</th>
<th valign="top">

 



</th>
</tr>
<tr>
<td valign="top">

--config



</td>
<td valign="top">

Specifies the location of the configuration file. See [Specify the Location of the Configuration File](Specify_the_Location_of_the_Configuration_File_e57288d.md).



</td>
</tr>
<tr>
<td valign="top">

--info



</td>
<td valign="top">

Displays version and current context. Note that this option only works on its own \(`btp --info)` and cannot be added to other command calls. You can also just use `btp` to display the info. See [View Version and Current Context](View_Version_and_Current_Context_9c29222.md).



</td>
</tr>
<tr>
<td valign="top">

--help



</td>
<td valign="top">

Displays help. See [Get Help](Get_Help_f8fd1e5.md).



</td>
</tr>
<tr>
<td valign="top">

--verbose



</td>
<td valign="top">

Prints tracing information for support. See [Troubleshooting and Support](Troubleshooting_and_Support_4023e15.md).



</td>
</tr>
<tr>
<td valign="top">

--format



</td>
<td valign="top">

Changes the output format of a command to JSON. See [Change the Output Format to JSON](Change_the_Output_Format_to_JSON_dcb85b7.md).



</td>
</tr>
</table>

**Related Information**  


[Commands in the btp CLI](Commands_in_the_btp_CLI_a03a555.md "A list of all tasks and respective commands that are available in the SAP BTP command line interface (btp CLI).")

