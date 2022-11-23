# Clean Code
Clean = Readable + Understanding
<br>

# Naming

## Common Prefix

  - is

  - can

  - has/icludes/contains

  - should/needs
<br>
  
## Create/Destroy

 <table class="table table-bordered table-striped table-condensed">
	<tbody>
		<tr>
			<td>Create</td>
			<td>Create an instance, used in instantiated and factory methods</td>
		</tr>
		<tr>
			<td>Initialize</td>
			<td>Initializes the properties and settings for the instance</td>
		</tr>
		<tr>
			<td>Uninitialize</td>
			<td>Clean up the properties and Settings of the instance, as&nbsp;opposed&nbsp;to Initialize</td>
		</tr>
		<tr>
			<td>Load</td>
			<td>Load content from the configuration</td>
		</tr>
		<tr>
			<td>Destroy</td>
			<td>Destroy instance</td>
		</tr>
	</tbody>
</table>
<br>

## Get/Set
<table class="table table-bordered table-striped table-condensed">
	<tbody>
		<tr>
			<td>Get</td>
			<td>Get properties,&nbsp;things you can get directly</td>
		</tr>
		<tr>
			<td>Fetch</td>
			<td>Data from network</td>
		</tr>
		<tr>
			<td>Calculate</td>
			<td>Data need to be calculated</td>
		</tr>
		<tr>
			<td>Read</td>
			<td>Data from files or configurations</td>
		</tr>
		<tr>
			<td>Query</td>
			<td>Data from DB</td>
		</tr>
		<tr>
			<td>Find</td>
			<td>Data from DB or list container</td>
		</tr>
		<tr>
			<td>Receive</td>
			<td>Receive files or messages</td>
		</tr>
		<tr>
			<td>Pull</td>
			<td>Pull</td>
		</tr>
		<tr>
			<td>Set</td>
			<td>Set properties</td>
		</tr>
		<tr>
			<td>Write</td>
			<td>Write into files or configuration</td>
		</tr>
		<tr>
			<td>Put</td>
			<td>Put in</td>
		</tr>
		<tr>
			<td>Push</td>
			<td>Save in, push messages</td>
		</tr>
	</tbody>
</table>
<br>

## Update

<table class="table table-bordered table-striped table-condensed">
	<tbody>
		<tr>
			<td>Reset</td>
			<td>Reset sign or status</td>
		</tr>
		<tr>
			<td>Refresh</td>
			<td>Refresh page or cache</td>
		</tr>
		<tr>
			<td>Update</td>
			<td>Update configuration or status</td>
		</tr>
	</tbody>
</table>
<br>

## Add/Remove
<table class="table table-bordered table-striped table-condensed">
	<tbody>
		<tr>
			<td>Add</td>
			<td>Add things</td>
		</tr>
		<tr>
			<td>Append</td>
			<td>Add to the tail</td>
		</tr>
		<tr>
			<td>Insert</td>
			<td>Insert someplace</td>
		</tr>
		<tr>
			<td>Delete</td>
			<td>Delete&nbsp;&asymp; Remove</td>
		</tr>
		<tr>
			<td>Remove</td>
			<td>Remove&nbsp;&asymp;&nbsp;Delete</td>
		</tr>
	</tbody>
</table>
<br>

## Start/Stop
<table class="table table-bordered table-striped table-condensed">
	<tbody>
		<tr>
			<td>Open</td>
			<td>Open file</td>
		</tr>
		<tr>
			<td>Start</td>
			<td>Start workflow</td>
		</tr>
		<tr>
			<td>Launch</td>
			<td>Launch program or server</td>
		</tr>
		<tr>
			<td>Close</td>
			<td>Close file</td>
		</tr>
		<tr>
			<td>Stop</td>
			<td>Stop workflow</td>
		</tr>
		<tr>
			<td>Pause</td>
			<td>Pause workflow which would start again</td>
		</tr>
		<tr>
			<td>Finish</td>
			<td>Workflow done</td>
		</tr>
	</tbody>
</table>
<br>

## Handle data from list
<table class="table table-bordered table-striped table-condensed">
	<tbody>
		<tr>
			<td>Filter</td>
			<td>Filter data with conditions</td>
		</tr>
		<tr>
			<td>Merge</td>
			<td>Merge data with conditions</td>
		</tr>
		<tr>
			<td>Concat</td>
			<td>Add to the tail</td>
		</tr>
		<tr>
			<td>Split</td>
			<td>Split</td>
		</tr>
		<tr>
			<td>Deduplicate</td>
			<td>Remove duplicate</td>
		</tr>
		<tr>
			<td>Reverse</td>
			<td>Reverse</td>
		</tr>
		<tr>
			<td>Sort</td>
			<td>Sort</td>
		</tr>
		<tr>
			<td>Fill</td>
			<td>Overwrite data</td>
		</tr>
	</tbody>
</table>
<br>

## Common verbs
<table class="table table-bordered table-striped table-condensed">
	<tbody>
		<tr>
			<td>Parse</td>
			<td>Parse to a specific format, parse and extract content</td>
		</tr>
		<tr>
			<td>Analyse</td>
			<td>Data that can&nbsp; not easily get</td>
		</tr>
		<tr>
			<td>Convert</td>
			<td>Convert to another type类型转换(通常用于从一个类型转换到另一种类型)</td>
		</tr>
		<tr>
			<td>Format</td>
			<td>Format data格式化数据</td>
		</tr>
		<tr>
			<td>Validate</td>
			<td>Data&nbsp;Verification</td>
		</tr>
		<tr>
			<td>Ensure</td>
			<td>Validate the&nbsp;expected value</td>
		</tr>
		<tr>
			<td>Compose</td>
			<td>Compose multiple parts to a result</td>
		</tr>
		<tr>
			<td>Encode</td>
			<td>Encode</td>
		</tr>
		<tr>
			<td>Decode</td>
			<td>Decode</td>
		</tr>
		<tr>
			<td>Encrypt</td>
			<td>Encrypt</td>
		</tr>
		<tr>
			<td>Decrypt</td>
			<td>Decrypt</td>
		</tr>
		<tr>
			<td>Backup</td>
			<td>Backup</td>
		</tr>
		<tr>
			<td>Restore</td>
			<td>Restore</td>
		</tr>
		<tr>
			<td>Import</td>
			<td>Import from a special format file</td>
		</tr>
		<tr>
			<td>Export</td>
			<td>Export to a special format file</td>
		</tr>
		<tr>
			<td>Compress</td>
			<td>Compress</td>
		</tr>
		<tr>
			<td>Decompress</td>
			<td>Decompress</td>
		</tr>
	</tbody>
</table>
<br>
