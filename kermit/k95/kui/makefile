PROJ = kui

OUTDIR = .\win95

all: $(OUTDIR)\$(PROJ).exe 

KUIOBJS = \
    $(OUTDIR)\kregedit.obj $(OUTDIR)\ksysmets.obj     \
    $(OUTDIR)\ksplash.obj  $(OUTDIR)\ikui.obj     $(OUTDIR)\kprogres.obj \
    $(OUTDIR)\ikterm.obj   $(OUTDIR)\ikcmd.obj    $(OUTDIR)\kuidef.obj   \
    $(OUTDIR)\karray.obj   $(OUTDIR)\khwndset.obj $(OUTDIR)\kwin.obj     \
    $(OUTDIR)\kszpopup.obj $(OUTDIR)\kflstat.obj  $(OUTDIR)\kcustdlg.obj \
    $(OUTDIR)\kmenu.obj    $(OUTDIR)\kstatus.obj  $(OUTDIR)\ktoolbar.obj \
    $(OUTDIR)\kscroll.obj  $(OUTDIR)\kcmdproc.obj $(OUTDIR)\kcmdterm.obj \
    $(OUTDIR)\kcmdprot.obj $(OUTDIR)\kcmdmous.obj $(OUTDIR)\kcmdscri.obj \
    $(OUTDIR)\kcmdup.obj   $(OUTDIR)\kcmddown.obj $(OUTDIR)\kcmdlog.obj  \
    $(OUTDIR)\kcmdcom.obj  $(OUTDIR)\kprop.obj    $(OUTDIR)\kfont.obj    \
    $(OUTDIR)\kfontdlg.obj $(OUTDIR)\kcolor.obj   $(OUTDIR)\kabout.obj   \
    $(OUTDIR)\kflname.obj  $(OUTDIR)\kdwnload.obj $(OUTDIR)\kupload.obj  \
    $(OUTDIR)\kuikey.obj   $(OUTDIR)\kclient.obj  \
    $(OUTDIR)\kcliserv.obj $(OUTDIR)\kappwin.obj  $(OUTDIR)\kcserver.obj \
    $(OUTDIR)\kcommand.obj $(OUTDIR)\ktermin.obj  $(OUTDIR)\kui.obj

RC_DEP = icon1.ico resource.h kui.rc

KERMITDIR = \kui\kermit

#--------------------------------------------------------------------------
# Dependencies

$(OUTDIR)\kabout.obj: kabout.cxx kabout.hxx kwin.hxx kuidef.h resource.h
$(OUTDIR)\kcmdcom.obj: kcmdcom.cxx kcmdcom.hxx kcmdproc.hxx kuidef.h resource.h
$(OUTDIR)\kcmddown.obj: kcmddown.cxx kcmddown.hxx kcmdproc.hxx kuidef.h resource.h
$(OUTDIR)\kcmdlog.obj: kcmdlog.cxx kcmdlog.hxx kcmdproc.hxx kuidef.h resource.h
$(OUTDIR)\kcmdmous.obj: kcmdmous.cxx kcmdmous.hxx kcmdproc.hxx kuidef.h resource.h karray.hxx
$(OUTDIR)\kcmdprot.obj: kcmdprot.cxx kcmdprot.hxx kcmdproc.hxx kuidef.h resource.h kcmd.h
$(OUTDIR)\kcmdscri.obj: kcmdscri.cxx kcmdscri.hxx kcmdproc.hxx kuidef.h resource.h
$(OUTDIR)\kcmdterm.obj: kcmdterm.cxx kcmdterm.hxx kcmdproc.hxx kuidef.h resource.h kcmd.h kdefs.h ikcmd.h
$(OUTDIR)\kcmdup.obj: kcmdup.cxx kcmdup.hxx kcmdproc.hxx kuidef.h resource.h
$(OUTDIR)\kcolor.obj: kcolor.cxx kcolor.hxx kwin.hxx kuidef.h resource.h
$(OUTDIR)\KUIKEY.obj: KUIKEY.CXX kuidef.h resource.h
$(OUTDIR)\kdwnload.obj: kdwnload.cxx kdwnload.hxx kwin.hxx kuidef.h resource.h kprop.hxx kprop.h
$(OUTDIR)\kflstat.obj: kflstat.cxx kflstat.hxx kwin.hxx kuidef.h resource.h kflstat.h karray.hxx kprogres.hxx
$(OUTDIR)\kmenu.obj: kmenu.cxx kmenu.hxx kuidef.h resource.h kwin.hxx ksysmets.hxx
$(OUTDIR)\kprop.obj: kprop.cxx kprop.hxx kprop.h kuidef.h resource.h kwin.hxx kcmdproc.hxx kcmdcom.hxx kcmdup.hxx kcmddown.hxx kcmdlog.hxx kcmdterm.hxx kcmdprot.hxx kcmdmous.hxx kcmdscri.hxx ikterm.h
$(OUTDIR)\kscroll.obj: kscroll.cxx kscroll.hxx kwin.hxx kuidef.h resource.h ikextern.h
$(OUTDIR)\kstatus.obj: kstatus.cxx kstatus.hxx kwin.hxx kuidef.h resource.h khwndset.hxx ksysmets.hxx kcustdlg.hxx karray.hxx
$(OUTDIR)\KWIN.obj: KWIN.CXX kwin.hxx kuidef.h resource.h khwndset.hxx
$(OUTDIR)\ksplash.obj: ksplash.cxx ksplash.hxx kuidef.h resource.h kfont.hxx ksysmets.hxx ikterm.h
$(OUTDIR)\kuidef.obj: kuidef.cxx kuidef.h resource.h
$(OUTDIR)\ktermin.obj: ktermin.cxx ktermin.hxx kappwin.hxx kwin.hxx kuidef.h resource.h kmenu.hxx ktoolbar.hxx kstatus.hxx kclient.hxx kprop.hxx kprop.h kupload.hxx kdwnload.hxx kfont.hxx kflname.hxx ksysmets.hxx ikcmd.h kdefs.h ikterm.h ikui.h
$(OUTDIR)\kupload.obj: kupload.cxx kupload.hxx kwin.hxx kuidef.h resource.h kprop.hxx kprop.h kflstat.hxx karray.hxx kflname.hxx
$(OUTDIR)\kcmdproc.obj: kcmdproc.cxx kcmdproc.hxx kuidef.h resource.h karray.hxx ikcmd.h kdefs.h
$(OUTDIR)\kcliserv.obj: kcliserv.cxx kcliserv.hxx kclient.hxx kwin.hxx kuidef.h resource.h
$(OUTDIR)\kcserver.obj: kcserver.cxx kcserver.hxx kappwin.hxx kwin.hxx kuidef.h resource.h kcliserv.hxx kclient.hxx kstatus.hxx ktoolbar.hxx kmenu.hxx ksysmets.hxx ikterm.h
$(OUTDIR)\khwndset.obj: khwndset.cxx khwndset.hxx kuidef.h resource.h karray.hxx
$(OUTDIR)\KFONTDLG.obj: KFONTDLG.CXX kfontdlg.hxx kwin.hxx kuidef.h resource.h khwndset.hxx
$(OUTDIR)\kcommand.obj: kcommand.cxx kcommand.hxx kappwin.hxx kwin.hxx kuidef.h resource.h kclient.hxx kstatus.hxx ktoolbar.hxx kmenu.hxx ksysmets.hxx ikterm.h
$(OUTDIR)\kregedit.obj: kregedit.cxx kregedit.hxx kuidef.h resource.h
$(OUTDIR)\karray.obj: karray.cxx karray.hxx kuidef.h resource.h
$(OUTDIR)\Kui.obj: Kui.cxx kui.hxx kuidef.h resource.h ktermin.hxx kappwin.hxx kwin.hxx kcommand.hxx kcserver.hxx kflstat.hxx khwndset.hxx kflstat.h ikui.h ikcmd.h kdefs.h
$(OUTDIR)\kfont.obj: kfont.cxx kfont.hxx kuidef.h resource.h karray.hxx
$(OUTDIR)\Ksysmets.obj: Ksysmets.cxx ksysmets.hxx kuidef.h resource.h
$(OUTDIR)\kflname.obj: kflname.cxx kflname.hxx karray.hxx kuidef.h resource.h ikcmd.h kdefs.h ikterm.h
$(OUTDIR)\ktoolbar.obj: ktoolbar.cxx ktoolbar.hxx kwin.hxx kuidef.h resource.h khwndset.hxx ikcmd.h kdefs.h
$(OUTDIR)\Kclient.obj: Kclient.cxx kclient.hxx kwin.hxx kuidef.h resource.h kscroll.hxx khwndset.hxx ksysmets.hxx kfont.hxx karray.hxx ikterm.h ikcmd.h kdefs.h
$(OUTDIR)\Kcustdlg.obj: Kcustdlg.cxx kcustdlg.hxx kwin.hxx kuidef.h resource.h kstatus.hxx khwndset.hxx kui.hxx ksysmets.hxx
$(OUTDIR)\KPROGRES.obj: KPROGRES.CXX kprogres.hxx kuidef.h resource.h ksysmets.hxx
$(OUTDIR)\kszpopup.obj: kszpopup.CXX kszpopup.hxx kwin.hxx kuidef.h resource.h kfont.hxx
$(OUTDIR)\Ikui.obj: Ikui.cxx ikui.h ksplash.hxx kuidef.h resource.h kui.hxx kregedit.hxx ksysmets.hxx khwndset.hxx
$(OUTDIR)\Kappwin.obj: Kappwin.cxx kappwin.hxx kwin.hxx kuidef.h resource.h kmenu.hxx ktoolbar.hxx kstatus.hxx kclient.hxx kfontdlg.hxx kcolor.hxx kabout.hxx kfont.hxx ksysmets.hxx kszpopup.hxx ikterm.h ikcmd.h kdefs.h

$(OUTDIR)\ikterm.obj: ikterm.cxx ikterm.h ikui.h \
    $(KERMITDIR)\ckcdeb.h $(KERMITDIR)\ckcker.h $(KERMITDIR)\ckcasc.h \
    $(KERMITDIR)\ckcxla.h $(KERMITDIR)\ckcnet.h $(KERMITDIR)\ckuusr.h \
    $(KERMITDIR)\ckopcf.h $(KERMITDIR)\ckocon.h $(KERMITDIR)\ckokey.h \
    $(KERMITDIR)\ckcuni.h

$(OUTDIR)\ikcmd.obj: ikcmd.c ikcmd.h kdefs.h \
    $(KERMITDIR)\ckcdeb.h $(KERMITDIR)\ckcker.h $(KERMITDIR)\ckcasc.h \
    $(KERMITDIR)\ckcxla.h $(KERMITDIR)\ckcnet.h $(KERMITDIR)\ckuusr.h \
    $(KERMITDIR)\ckopcf.h $(KERMITDIR)\ckocon.h $(KERMITDIR)\ckokey.h \
    $(KERMITDIR)\ckcxxx.h $(KERMITDIR)\ckcuni.h

!ifdef NODEBUG
# Non-debugging options

!MESSAGE 32-bit Non-debugging build

CFLAGS    = /c /W3 /MD /G5 /Ox /GA /J /nologo /Fo$(OUTDIR)\ /I$(KERMITDIR) -noBool
CDEFINES  = /D_MT /DSTRICT /D_X86_ /DNDEBUG /D_WINDOWS /DWIN32 /DWIN32_LEAN_AND_MEAN \
                -DNT -DOS2 -DDYNAMIC -DKANJI -DNETCONN -DTCPSOCKET \
                -DHADDRLIST -DSCRIPTTERM -DOS2MOUSE -DCK_XYZ -DOS2TEST -DKUI
LFLAGS    = /NOD /NOLOGO /SUBSYSTEM:windows
RCFLAGS   = /r
RCDEFINES = /dNDEBUG /dWIN32
MAPFILE   =

!else
# Debugging options

!MESSAGE 32-bit Debugging build

CFLAGS    = /c /W3 /MD /Od /Zi /J /Fd$(OUTDIR)\$(PROJ).pdb /nologo -noBool \
                /Fo$(OUTDIR)\ /I$(KERMITDIR)
CDEFINES  = /D_MT /D_X86_ /DSTRICT /D_DEBUG /D_WINDOWS /DWIN32 /DWIN32_LEAN_AND_MEAN \
                -DNT -DOS2 -DDYNAMIC -DKANJI -DNETCONN -DTCPSOCKET -DSUPERLAT\
                -DHADDRLIST -DSCRIPTTERM -DOS2MOUSE -DRLOGCODE \
                -DNETFILE -DONETERMUPD -DKUI

LFLAGS    = /NOD /NOLOGO /DEBUG:full /DEBUGTYPE:cv /SUBSYSTEM:windows
RCFLAGS   = /r
RCDEFINES = /d_DEBUG /dWIN32
MAPFILE   = /map:$(OUTDIR)\$(PROJ).map

!endif

#--------------------------------------------------------------------------
# 32-bit Build Rules

$(OUTDIR):
    if not exist $(OUTDIR)\nul mkdir $(OUTDIR)

$(OUTDIR)\$(PROJ).EXE: $(OUTDIR) $(KUIOBJS) $(OUTDIR)\$(PROJ).res
!ifdef VCSID
    cd $(KERMITDIR)
    set PLATFORM=NT
    nmake /nologo /e /f ckoker.mak kuid
!endif

$(OUTDIR)\$(PROJ).res: $(PROJ).rc $(RC_DEP)
    rc $(RCFLAGS) $(RCDEFINES) /fo$(OUTDIR)\$(PROJ).res $(PROJ).rc

.c{$(OUTDIR)}.obj: 
    cl $(CFLAGS) $(CDEFINES) $<

.cxx{$(OUTDIR)}.obj: 
    cl $(CFLAGS) $(CDEFINES) $<