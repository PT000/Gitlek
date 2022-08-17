#Test text
# Gitlek
# Mera tex
<h3> HTML-txt   </h3>
<h4> Mera HTML  </h4>
mermaid
erDiagram
    CUSTOMER ||--o{ ORDER : places
        CUSTOMER {
	        string name
		string custNumber
		string sector
				    }
   ORDER ||--|{ LINE-ITEM : contains
	ORDER {
	        int orderNumber
		string deliveryAddress
			            }
  LINE-ITEM {
		string productCode
		int quantity
	        float pricePerUnit
				   }
