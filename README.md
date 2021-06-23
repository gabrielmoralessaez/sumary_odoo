# sumary_odoo
Pycharm
Ctrl+Shif+F para buscar en Pycharm
Ctrl+D dupicar 
ctrl+ alt+ L para indexar codigo
ctrl+A todo es seleccionado

manifest: category buscar con comando anterior
_name= crea una nueva tabla en la base de datos postgres
odoo automaticamente crea id, date y otros 5 o 6 fields automaticos
al activar el modo desarrollador se agrega el tecnico te vas a estructuras de base de datos y modelos y te aparecen todos
char: tipo texto seleccion: combobox

Si en seguridad borro el grupo es global para todos los usuarios y se agrega al manifest

Buscar con Ctrl+Shif+F, activar debug, editar accion, ID externo, sale.action_orders copiamos solo action_orders, con find in file 
la linea despues de <field name="arch" type="xml"> define si es form tree kanban
  
  
  en la parte superior al tener el debug dice model="sale.order" este es el nombre del modelo
  
  para buscar la depends debo buscar el nombre ejemplo sale.order y el nombre del modulo es la dependencia
  
  con el Ctrl+Shif+F buscar name="inherit_id"

<record id="view_order_form_inherit" model="ir.ui.view">
            <field name="name">sale.order.inherit</field>
            <field name="model">sale.order</field>
            <field name="inherit_id" ref="sale.view_order_form"/>
            <field name="arch" type="xml">
           </field>
  </record>
  en el record id se agrega el nombre del ref despues del punto y se agrega inherit, el modelo es el modelo heredado
  
