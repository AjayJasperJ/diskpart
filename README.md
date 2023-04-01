# diskpart
Reset crashed drive

Diskpart
list disk
select disk _
clean
format fs=ntfs
assign
