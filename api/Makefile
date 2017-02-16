# Copyright 2012 The Go Authors. All rights reserved.
# Use of this source code is governed by a BSD-style
# license that can be found in the LICENSE file.

all: zapi_unix.go


zapi_unix.go: api.go
	./mksyscall_unix.pl $^ \
		| gofmt \
		> $@
