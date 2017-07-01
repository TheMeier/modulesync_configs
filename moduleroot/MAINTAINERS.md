## Maintenance

<% if @configs['maintainers'] -%>
Maintainers:
<%   @configs['maintainers'].each do |name| -%>
  - <%= name %>
<%   end -%>
<% end -%>

Tickets: https://github.com/TheMeier/<%= @configs[:puppet_module] -%>/issues
