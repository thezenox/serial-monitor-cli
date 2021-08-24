 # NOTICES AND INFORMATION

 Do Not Translate or Localize

 This software incorporates material from third parties. Microsoft makes certain
 open source code available at https://3rdpartysource.microsoft.com, or you may
 send a check or money order for US $5.00, including the product name, the open
 source component name, and version number, to:

 Source Code Compliance Team
 Microsoft Corporation
 One Microsoft Way
 Redmond, WA 98052
 USA

 Notwithstanding any other terms, you may reverse engineer this software to the
 extent required to debug changes to any libraries licensed under the GNU Lesser
 General Public License.

## Python 3

### License

    1. This LICENSE AGREEMENT is between the Python Software Foundation ("PSF"), and
    the Individual or Organization ("Licensee") accessing and otherwise using Python
    3.9.6 software in source or binary form and its associated documentation.

    2. Subject to the terms and conditions of this License Agreement, PSF hereby
    grants Licensee a nonexclusive, royalty-free, world-wide license to reproduce,
    analyze, test, perform and/or display publicly, prepare derivative works,
    distribute, and otherwise use Python 3.9.6 alone or in any derivative
    version, provided, however, that PSF's License Agreement and PSF's notice of
    copyright, i.e., "Copyright © 2001-2021 Python Software Foundation; All Rights
    Reserved" are retained in Python 3.9.6 alone or in any derivative version
    prepared by Licensee.

    3. In the event Licensee prepares a derivative work that is based on or
    incorporates Python 3.9.6 or any part thereof, and wants to make the
    derivative work available to others as provided herein, then Licensee hereby
    agrees to include in any such work a brief summary of the changes made to Python
    3.9.6.

    4. PSF is making Python 3.9.6 available to Licensee on an "AS IS" basis.
    PSF MAKES NO REPRESENTATIONS OR WARRANTIES, EXPRESS OR IMPLIED.  BY WAY OF
    EXAMPLE, BUT NOT LIMITATION, PSF MAKES NO AND DISCLAIMS ANY REPRESENTATION OR
    WARRANTY OF MERCHANTABILITY OR FITNESS FOR ANY PARTICULAR PURPOSE OR THAT THE
    USE OF PYTHON 3.9.6 WILL NOT INFRINGE ANY THIRD PARTY RIGHTS.

    5. PSF SHALL NOT BE LIABLE TO LICENSEE OR ANY OTHER USERS OF PYTHON 3.9.6
    FOR ANY INCIDENTAL, SPECIAL, OR CONSEQUENTIAL DAMAGES OR LOSS AS A RESULT OF
    MODIFYING, DISTRIBUTING, OR OTHERWISE USING PYTHON 3.9.6, OR ANY DERIVATIVE
    THEREOF, EVEN IF ADVISED OF THE POSSIBILITY THEREOF.

    6. This License Agreement will automatically terminate upon a material breach of
    its terms and conditions.

    7. Nothing in this License Agreement shall be deemed to create any relationship
    of agency, partnership, or joint venture between PSF and Licensee.  This License
    Agreement does not grant permission to use PSF trademarks or trade name in a
    trademark sense to endorse or promote products or services of Licensee, or any
    third party.

    8. By copying, installing or otherwise using Python 3.9.6, Licensee agrees
    to be bound by the terms and conditions of this License Agreement.

### Aditional Attributions
#### Mersenne Twister
The _random module includes code based on a download from http://www.math.sci.hiroshima-u.ac.jp/~m-mat/MT/MT2002/emt19937ar.html. The following are the verbatim comments from the original code:

A C-program for MT19937, with initialization improved 2002/1/26.
Coded by Takuji Nishimura and Makoto Matsumoto.

Before using, initialize the state by using init_genrand(seed)
or init_by_array(init_key, key_length).

    Copyright (C) 1997 - 2002, Makoto Matsumoto and Takuji Nishimura,
    All rights reserved.

    Redistribution and use in source and binary forms, with or without
    modification, are permitted provided that the following conditions
    are met:

    1. Redistributions of source code must retain the above copyright
        notice, this list of conditions and the following disclaimer.

    2. Redistributions in binary form must reproduce the above copyright
        notice, this list of conditions and the following disclaimer in the
        documentation and/or other materials provided with the distribution.

    3. The names of its contributors may not be used to endorse or promote
        products derived from this software without specific prior written
        permission.

    THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
    "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
    LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
    A PARTICULAR PURPOSE ARE DISCLAIMED.  IN NO EVENT SHALL THE COPYRIGHT OWNER OR
    CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL,
    EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
    PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR
    PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF
    LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING
    NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
    SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.


    Any feedback is very welcome.
    http://www.math.sci.hiroshima-u.ac.jp/~m-mat/MT/emt.html
    email: m-mat @ math.sci.hiroshima-u.ac.jp (remove space)

#### Sockets
The socket module uses the functions, getaddrinfo(), and getnameinfo(), which are coded in separate source files from the WIDE Project, http://www.wide.ad.jp/.

    Copyright (C) 1995, 1996, 1997, and 1998 WIDE Project.
    All rights reserved.

    Redistribution and use in source and binary forms, with or without
    modification, are permitted provided that the following conditions
    are met:
    1. Redistributions of source code must retain the above copyright
    notice, this list of conditions and the following disclaimer.
    2. Redistributions in binary form must reproduce the above copyright
    notice, this list of conditions and the following disclaimer in the
    documentation and/or other materials provided with the distribution.
    3. Neither the name of the project nor the names of its contributors
    may be used to endorse or promote products derived from this software
    without specific prior written permission.

    THIS SOFTWARE IS PROVIDED BY THE PROJECT AND CONTRIBUTORS ``AS IS'' AND
    ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
    IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
    ARE DISCLAIMED.  IN NO EVENT SHALL THE PROJECT OR CONTRIBUTORS BE LIABLE
    FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
    DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS
    OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION)
    HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT
    LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY
    OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF
    SUCH DAMAGE.


#### Asynchronous socket services
The asynchat and asyncore modules contain the following notice:

    Copyright 1996 by Sam Rushing

                            All Rights Reserved

    Permission to use, copy, modify, and distribute this software and
    its documentation for any purpose and without fee is hereby
    granted, provided that the above copyright notice appear in all
    copies and that both that copyright notice and this permission
    notice appear in supporting documentation, and that the name of Sam
    Rushing not be used in advertising or publicity pertaining to
    distribution of the software without specific, written prior
    permission.

    SAM RUSHING DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE,
    INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS, IN
    NO EVENT SHALL SAM RUSHING BE LIABLE FOR ANY SPECIAL, INDIRECT OR
    CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS
    OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT,
    NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN
    CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.

#### Cookie management
The http.cookies module contains the following notice:

    Copyright 2000 by Timothy O'Malley <timo@alum.mit.edu>

                All Rights Reserved

    Permission to use, copy, modify, and distribute this software
    and its documentation for any purpose and without fee is hereby
    granted, provided that the above copyright notice appear in all
    copies and that both that copyright notice and this permission
    notice appear in supporting documentation, and that the name of
    Timothy O'Malley  not be used in advertising or publicity
    pertaining to distribution of the software without specific, written
    prior permission.

    Timothy O'Malley DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS
    SOFTWARE, INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY
    AND FITNESS, IN NO EVENT SHALL Timothy O'Malley BE LIABLE FOR
    ANY SPECIAL, INDIRECT OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
    WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS,
    WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS
    ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR
    PERFORMANCE OF THIS SOFTWARE.

#### Execution tracing
The trace module contains the following notice:

    portions copyright 2001, Autonomous Zones Industries, Inc., all rights...
    err...  reserved and offered to the public under the terms of the
    Python 2.2 license.
    Author: Zooko O'Whielacronx
    http://zooko.com/
    mailto:zooko@zooko.com

    Copyright 2000, Mojam Media, Inc., all rights reserved.
    Author: Skip Montanaro

    Copyright 1999, Bioreason, Inc., all rights reserved.
    Author: Andrew Dalke

    Copyright 1995-1997, Automatrix, Inc., all rights reserved.
    Author: Skip Montanaro

    Copyright 1991-1995, Stichting Mathematisch Centrum, all rights reserved.


    Permission to use, copy, modify, and distribute this Python software and
    its associated documentation for any purpose without fee is hereby
    granted, provided that the above copyright notice appears in all copies,
    and that both that copyright notice and this permission notice appear in
    supporting documentation, and that the name of neither Automatrix,
    Bioreason or Mojam Media be used in advertising or publicity pertaining to
    distribution of the software without specific, written prior permission.

#### UUencode and UUdecode functions
The uu module contains the following notice:

    Copyright 1994 by Lance Ellinghouse
    Cathedral City, California Republic, United States of America.
                        All Rights Reserved
    Permission to use, copy, modify, and distribute this software and its
    documentation for any purpose and without fee is hereby granted,
    provided that the above copyright notice appear in all copies and that
    both that copyright notice and this permission notice appear in
    supporting documentation, and that the name of Lance Ellinghouse
    not be used in advertising or publicity pertaining to distribution
    of the software without specific, written prior permission.
    LANCE ELLINGHOUSE DISCLAIMS ALL WARRANTIES WITH REGARD TO
    THIS SOFTWARE, INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND
    FITNESS, IN NO EVENT SHALL LANCE ELLINGHOUSE CENTRUM BE LIABLE
    FOR ANY SPECIAL, INDIRECT OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
    WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
    ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT
    OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.

    Modified by Jack Jansen, CWI, July 1995:
    - Use binascii module to do the actual line-by-line conversion
    between ascii and binary. This results in a 1000-fold speedup. The C
    version is still 5 times faster, though.
    - Arguments more compliant with Python standard

#### XML Remote Procedure Calls
The xmlrpc.client module contains the following notice:

        The XML-RPC client interface is

    Copyright (c) 1999-2002 by Secret Labs AB
    Copyright (c) 1999-2002 by Fredrik Lundh

    By obtaining, using, and/or copying this software and/or its
    associated documentation, you agree that you have read, understood,
    and will comply with the following terms and conditions:

    Permission to use, copy, modify, and distribute this software and
    its associated documentation for any purpose and without fee is
    hereby granted, provided that the above copyright notice appears in
    all copies, and that both that copyright notice and this permission
    notice appear in supporting documentation, and that the name of
    Secret Labs AB or the author not be used in advertising or publicity
    pertaining to distribution of the software without specific, written
    prior permission.

    SECRET LABS AB AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD
    TO THIS SOFTWARE, INCLUDING ALL IMPLIED WARRANTIES OF MERCHANT-
    ABILITY AND FITNESS.  IN NO EVENT SHALL SECRET LABS AB OR THE AUTHOR
    BE LIABLE FOR ANY SPECIAL, INDIRECT OR CONSEQUENTIAL DAMAGES OR ANY
    DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS,
    WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS
    ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE
    OF THIS SOFTWARE.

#### test_epoll
The test_epoll module contains the following notice:

    Copyright (c) 2001-2006 Twisted Matrix Laboratories.

    Permission is hereby granted, free of charge, to any person obtaining
    a copy of this software and associated documentation files (the
    "Software"), to deal in the Software without restriction, including
    without limitation the rights to use, copy, modify, merge, publish,
    distribute, sublicense, and/or sell copies of the Software, and to
    permit persons to whom the Software is furnished to do so, subject to
    the following conditions:

    The above copyright notice and this permission notice shall be
    included in all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
    EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
    MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
    NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
    LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
    OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
    WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

#### Select kqueue
The select module contains the following notice for the kqueue interface:

    Copyright (c) 2000 Doug White, 2006 James Knight, 2007 Christian Heimes
    All rights reserved.

    Redistribution and use in source and binary forms, with or without
    modification, are permitted provided that the following conditions
    are met:
    1. Redistributions of source code must retain the above copyright
    notice, this list of conditions and the following disclaimer.
    2. Redistributions in binary form must reproduce the above copyright
    notice, this list of conditions and the following disclaimer in the
    documentation and/or other materials provided with the distribution.

    THIS SOFTWARE IS PROVIDED BY THE AUTHOR AND CONTRIBUTORS ``AS IS'' AND
    ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
    IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
    ARE DISCLAIMED.  IN NO EVENT SHALL THE AUTHOR OR CONTRIBUTORS BE LIABLE
    FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
    DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS
    OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION)
    HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT
    LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY
    OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF
    SUCH DAMAGE.

#### SipHash24
The file Python/pyhash.c contains Marek Majkowski’ implementation of Dan Bernstein’s SipHash24 algorithm. It contains the following note:

    <MIT License>
    Copyright (c) 2013  Marek Majkowski <marek@popcount.org>

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in
    all copies or substantial portions of the Software.
    </MIT License>

    Original location:
    https://github.com/majek/csiphash/

    Solution inspired by code from:
    Samuel Neves (supercop/crypto_auth/siphash24/little)
    djb (supercop/crypto_auth/siphash24/little2)
    Jean-Philippe Aumasson (https://131002.net/siphash/siphash24.c)

#### strtod and dtoa
The file Python/dtoa.c, which supplies C functions dtoa and strtod for conversion of C doubles to and from strings, is derived from the file of the same name by David M. Gay, currently available from http://www.netlib.org/fp/. The original file, as retrieved on March 16, 2009, contains the following copyright and licensing notice:

    /****************************************************************
    *
    * The author of this software is David M. Gay.
    *
    * Copyright (c) 1991, 2000, 2001 by Lucent Technologies.
    *
    * Permission to use, copy, modify, and distribute this software for any
    * purpose without fee is hereby granted, provided that this entire notice
    * is included in all copies of any software which is or includes a copy
    * or modification of this software and in all copies of the supporting
    * documentation for such software.
    *
    * THIS SOFTWARE IS BEING PROVIDED "AS IS", WITHOUT ANY EXPRESS OR IMPLIED
    * WARRANTY.  IN PARTICULAR, NEITHER THE AUTHOR NOR LUCENT MAKES ANY
    * REPRESENTATION OR WARRANTY OF ANY KIND CONCERNING THE MERCHANTABILITY
    * OF THIS SOFTWARE OR ITS FITNESS FOR ANY PARTICULAR PURPOSE.
    *
    ***************************************************************/

#### OpenSSL
The modules hashlib, posix, ssl, crypt use the OpenSSL library for added performance if made available by the operating system. Additionally, the Windows and Mac OS X installers for Python may include a copy of the OpenSSL libraries, so we include a copy of the OpenSSL license here:

    LICENSE ISSUES
    ==============

    The OpenSSL toolkit stays under a dual license, i.e. both the conditions of
    the OpenSSL License and the original SSLeay license apply to the toolkit.
    See below for the actual license texts. Actually both licenses are BSD-style
    Open Source licenses. In case of any license issues related to OpenSSL
    please contact openssl-core@openssl.org.

    OpenSSL License
    ---------------

    /* ====================================================================
        * Copyright (c) 1998-2008 The OpenSSL Project.  All rights reserved.
        *
        * Redistribution and use in source and binary forms, with or without
        * modification, are permitted provided that the following conditions
        * are met:
        *
        * 1. Redistributions of source code must retain the above copyright
        *    notice, this list of conditions and the following disclaimer.
        *
        * 2. Redistributions in binary form must reproduce the above copyright
        *    notice, this list of conditions and the following disclaimer in
        *    the documentation and/or other materials provided with the
        *    distribution.
        *
        * 3. All advertising materials mentioning features or use of this
        *    software must display the following acknowledgment:
        *    "This product includes software developed by the OpenSSL Project
        *    for use in the OpenSSL Toolkit. (http://www.openssl.org/)"
        *
        * 4. The names "OpenSSL Toolkit" and "OpenSSL Project" must not be used to
        *    endorse or promote products derived from this software without
        *    prior written permission. For written permission, please contact
        *    openssl-core@openssl.org.
        *
        * 5. Products derived from this software may not be called "OpenSSL"
        *    nor may "OpenSSL" appear in their names without prior written
        *    permission of the OpenSSL Project.
        *
        * 6. Redistributions of any form whatsoever must retain the following
        *    acknowledgment:
        *    "This product includes software developed by the OpenSSL Project
        *    for use in the OpenSSL Toolkit (http://www.openssl.org/)"
        *
        * THIS SOFTWARE IS PROVIDED BY THE OpenSSL PROJECT ``AS IS'' AND ANY
        * EXPRESSED OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
        * IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
        * PURPOSE ARE DISCLAIMED.  IN NO EVENT SHALL THE OpenSSL PROJECT OR
        * ITS CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
        * SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT
        * NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
        * LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION)
        * HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT,
        * STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
        * ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED
        * OF THE POSSIBILITY OF SUCH DAMAGE.
        * ====================================================================
        *
        * This product includes cryptographic software written by Eric Young
        * (eay@cryptsoft.com).  This product includes software written by Tim
        * Hudson (tjh@cryptsoft.com).
        *
        */

    Original SSLeay License
    -----------------------

    /* Copyright (C) 1995-1998 Eric Young (eay@cryptsoft.com)
        * All rights reserved.
        *
        * This package is an SSL implementation written
        * by Eric Young (eay@cryptsoft.com).
        * The implementation was written so as to conform with Netscapes SSL.
        *
        * This library is free for commercial and non-commercial use as long as
        * the following conditions are aheared to.  The following conditions
        * apply to all code found in this distribution, be it the RC4, RSA,
        * lhash, DES, etc., code; not just the SSL code.  The SSL documentation
        * included with this distribution is covered by the same copyright terms
        * except that the holder is Tim Hudson (tjh@cryptsoft.com).
        *
        * Copyright remains Eric Young's, and as such any Copyright notices in
        * the code are not to be removed.
        * If this package is used in a product, Eric Young should be given attribution
        * as the author of the parts of the library used.
        * This can be in the form of a textual message at program startup or
        * in documentation (online or textual) provided with the package.
        *
        * Redistribution and use in source and binary forms, with or without
        * modification, are permitted provided that the following conditions
        * are met:
        * 1. Redistributions of source code must retain the copyright
        *    notice, this list of conditions and the following disclaimer.
        * 2. Redistributions in binary form must reproduce the above copyright
        *    notice, this list of conditions and the following disclaimer in the
        *    documentation and/or other materials provided with the distribution.
        * 3. All advertising materials mentioning features or use of this software
        *    must display the following acknowledgement:
        *    "This product includes cryptographic software written by
        *     Eric Young (eay@cryptsoft.com)"
        *    The word 'cryptographic' can be left out if the rouines from the library
        *    being used are not cryptographic related :-).
        * 4. If you include any Windows specific code (or a derivative thereof) from
        *    the apps directory (application code) you must include an acknowledgement:
        *    "This product includes software written by Tim Hudson (tjh@cryptsoft.com)"
        *
        * THIS SOFTWARE IS PROVIDED BY ERIC YOUNG ``AS IS'' AND
        * ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
        * IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
        * ARE DISCLAIMED.  IN NO EVENT SHALL THE AUTHOR OR CONTRIBUTORS BE LIABLE
        * FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
        * DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS
        * OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION)
        * HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT
        * LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY
        * OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF
        * SUCH DAMAGE.
        *
        * The licence and distribution terms for any publically available version or
        * derivative of this code cannot be changed.  i.e. this code cannot simply be
        * copied and put under another distribution licence
        * [including the GNU Public Licence.]
        */

#### expat
The pyexpat extension is built using an included copy of the expat sources unless the build is configured --with-system-expat:

    Copyright (c) 1998, 1999, 2000 Thai Open Source Software Center Ltd
                                and Clark Cooper

    Permission is hereby granted, free of charge, to any person obtaining
    a copy of this software and associated documentation files (the
    "Software"), to deal in the Software without restriction, including
    without limitation the rights to use, copy, modify, merge, publish,
    distribute, sublicense, and/or sell copies of the Software, and to
    permit persons to whom the Software is furnished to do so, subject to
    the following conditions:

    The above copyright notice and this permission notice shall be included
    in all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
    EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
    MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
    IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
    CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
    TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
    SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

#### libffi
The _ctypes extension is built using an included copy of the libffi sources unless the build is configured --with-system-libffi:

    Copyright (c) 1996-2008  Red Hat, Inc and others.

    Permission is hereby granted, free of charge, to any person obtaining
    a copy of this software and associated documentation files (the
    ``Software''), to deal in the Software without restriction, including
    without limitation the rights to use, copy, modify, merge, publish,
    distribute, sublicense, and/or sell copies of the Software, and to
    permit persons to whom the Software is furnished to do so, subject to
    the following conditions:

    The above copyright notice and this permission notice shall be included
    in all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED ``AS IS'', WITHOUT WARRANTY OF ANY KIND,
    EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
    MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
    NONINFRINGEMENT.  IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
    HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
    WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
    DEALINGS IN THE SOFTWARE.

#### zlib
The zlib extension is built using an included copy of the zlib sources if the zlib version found on the system is too old to be used for the build:

    Copyright (C) 1995-2011 Jean-loup Gailly and Mark Adler

    This software is provided 'as-is', without any express or implied
    warranty.  In no event will the authors be held liable for any damages
    arising from the use of this software.

    Permission is granted to anyone to use this software for any purpose,
    including commercial applications, and to alter it and redistribute it
    freely, subject to the following restrictions:

    1. The origin of this software must not be misrepresented; you must not
    claim that you wrote the original software. If you use this software
    in a product, an acknowledgment in the product documentation would be
    appreciated but is not required.

    2. Altered source versions must be plainly marked as such, and must not be
    misrepresented as being the original software.

    3. This notice may not be removed or altered from any source distribution.

    Jean-loup Gailly        Mark Adler
    jloup@gzip.org          madler@alumni.caltech.edu

#### cfuhash
The implementation of the hash table used by the tracemalloc is based on the cfuhash project:

    Copyright (c) 2005 Don Owens
    All rights reserved.

    This code is released under the BSD license:

    Redistribution and use in source and binary forms, with or without
    modification, are permitted provided that the following conditions
    are met:

    * Redistributions of source code must retain the above copyright
        notice, this list of conditions and the following disclaimer.

    * Redistributions in binary form must reproduce the above
        copyright notice, this list of conditions and the following
        disclaimer in the documentation and/or other materials provided
        with the distribution.

    * Neither the name of the author nor the names of its
        contributors may be used to endorse or promote products derived
        from this software without specific prior written permission.

    THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
    "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
    LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS
    FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE
    COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT,
    INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
    (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
    SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION)
    HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT,
    STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
    ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED
    OF THE POSSIBILITY OF SUCH DAMAGE.

#### libmpdec
The _decimal module is built using an included copy of the libmpdec library unless the build is configured --with-system-libmpdec:

    Copyright (c) 2008-2020 Stefan Krah. All rights reserved.

    Redistribution and use in source and binary forms, with or without
    modification, are permitted provided that the following conditions
    are met:

    1. Redistributions of source code must retain the above copyright
    notice, this list of conditions and the following disclaimer.

    2. Redistributions in binary form must reproduce the above copyright
    notice, this list of conditions and the following disclaimer in the
    documentation and/or other materials provided with the distribution.

    THIS SOFTWARE IS PROVIDED BY THE AUTHOR AND CONTRIBUTORS "AS IS" AND
    ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
    IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
    ARE DISCLAIMED.  IN NO EVENT SHALL THE AUTHOR OR CONTRIBUTORS BE LIABLE
    FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
    DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS
    OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION)
    HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT
    LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY
    OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF
    SUCH DAMAGE.

#### W3C C14N test suite
The C14N 2.0 test suite in the test package (Lib/test/xmltestdata/c14n-20/) was retrieved from the W3C website at https://www.w3.org/TR/xml-c14n2-testcases/ and is distributed under the 3-clause BSD license:

    Copyright (c) 2013 W3C(R) (MIT, ERCIM, Keio, Beihang),
    All Rights Reserved.

    Redistribution and use in source and binary forms, with or without
    modification, are permitted provided that the following conditions
    are met:

    * Redistributions of works must retain the original copyright notice,
    this list of conditions and the following disclaimer.
    * Redistributions in binary form must reproduce the original copyright
    notice, this list of conditions and the following disclaimer in the
    documentation and/or other materials provided with the distribution.
    * Neither the name of the W3C nor the names of its contributors may be
    used to endorse or promote products derived from this work without
    specific prior written permission.

    THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
    "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
    LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
    A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT
    OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
    SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT
    LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
    DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY
    THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
    (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
    OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.