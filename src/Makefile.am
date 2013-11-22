# Sources for network

module_DATA = \
  modules/DSL.rb \
  modules/Modem.rb \
  modules/ISDN.rb \
  modules/Provider.rb

client_DATA = \
  clients/isdn_proposal.rb \
  clients/modem_proposal.rb \
  clients/isdn.rb \
  clients/modem.rb \
  clients/dsl_proposal.rb \
  clients/dsl.rb \
  clients/provider.rb

ynclude3dir = @yncludedir@/network/provider
ynclude3_DATA = \
  include/network/provider/wizards.rb \
  include/network/provider/connection.rb \
  include/network/provider/dialogs.rb \
  include/network/provider/complex.rb \
  include/network/provider/provider.rb \
  include/network/provider/details.rb \
  include/network/provider/helps.rb \
  include/network/provider/texts.rb

ynclude4dir = @yncludedir@/network/isdn
ynclude4_DATA = \
  include/network/isdn/interface.rb \
  include/network/isdn/wizards.rb \
  include/network/isdn/config.rb \
  include/network/isdn/ip.rb \
  include/network/isdn/ifdetails.rb \
  include/network/isdn/complex.rb \
  include/network/isdn/lowlevel.rb \
  include/network/isdn/routines.rb

ynclude7dir = @yncludedir@/network/dsl
ynclude7_DATA = \
  include/network/dsl/wizards.rb \
  include/network/dsl/dialogs.rb \
  include/network/dsl/complex.rb

ynclude8dir = @yncludedir@/network/modem
ynclude8_DATA = \
  include/network/modem/wizards.rb \
  include/network/modem/dialogs.rb \
  include/network/modem/complex.rb

scrconf_DATA = \
  scrconf/providers.scr \
  scrconf/cfg_slmodemd.scr \
  scrconf/cfg_providers.scr \
  scrconf/isdn.scr

ydata_DATA = \
  data/modem-t35-keys.ycp

desktop_DATA = \
  desktop/isdn.desktop \
  desktop/provider.desktop \
  desktop/modem.desktop \
  desktop/dsl.desktop

EXTRA_DIST = \
  $(module_DATA) \
  $(client_DATA) \
  $(ynclude3_DATA) \
  $(ynclude4_DATA) \
  $(ynclude7_DATA) \
  $(ynclude8_DATA) \
  $(scrconf_DATA) \
  $(schemafiles_DATA) \
  $(ybin_SCRIPTS) \
  $(ydata_DATA) \
  $(desktop_DATA)

include $(top_srcdir)/Makefile.am.common
