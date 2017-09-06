
# Verkefni 1:
  
  ## Sindri:
  ### 1) Miðlarinn: "178.62.119.51".
  ### 2) HTTP/2 er með þjappaða headers, það er multiplexing sem leyfir tengingunni að vera send á sama tíma, lagar flestar villur með HTTP 1.0.
  
  ## Siggi:
  ### 1) Miðlarinn: "178.62.119.51".
  ### 2) HTTP 2.0 var búið til að leisa mörg af vandarmálunum með HTTP. HTTP 2.0 sendir allt í einu frekar en að package-a það niður.
  
# Verkefni 2:

  ## Sindri:
  ### 1)
  ##### a) Static routing væri að nota folder/file systemið sem notar spaghettí URL og helling af undirsíðum.
  ##### b) Dynamic routing væri að nota sömu síðuna aftur og aftur, en notar forritaðann kóða til að breyta til síðunni með því að senda gögnin í sem query requests í URL-inu... en URL-ið er ekki venulega spaghettí URL... heldur er oftast búið að gera það fancy.
  ### 2) 
  ##### front-end routing er basically þannig að þú ert með "controller" í view sem er að sækja gögn og vinna með það ánþess að refresh-a hinsvegar með back-end routing þá þarf serverinn alltaf að processa allt, og þá þarf clientinn alltaf að refresh-a.

  ## Siggi:
  ### 1)
  ##### a) static útfærslan væri fullt af undir síðum í möppu kerfi
  ##### b) dynamic útfærslan væri ein síða sem myndi færa þér mismunandi uplýsingar eftir því hvaða link havi verið smelt á.
  ### 2)
  ##### frontenda routing sníst um að sækja göggn og vinna með þau realtime ánþess að þurfa að refresha síðuni eins og í SPA.
  ##### backenda routing þarf að refresha til að sækja gögn.
  ##### bæði nota MVC.
