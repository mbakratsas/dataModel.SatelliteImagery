Entité : EOSatellitePlatform  
============================







- `id`  

<details><summary><strong>full yaml details</strong></summary>    

EOSatellitePlatform:    
  description: 'This entity contains a harmonised description of a generic EOSatellitePlatform made for the Satellite Imagerry domain. This entity is primarily associated with the Satellite platforms related to Earth Observation Analysis applications.'    
  properties:    
    platformID:    
      description: 'A mandatory text string used to declare the unique ID of the platform'    
      type: Property    
      x-ngsi:    
        model: https://schema.org/Text    
    platformNSSDCA:    
      description: 'A mandatory text string used to declare the unique mission id in the National Space Science Data Center Archive'    
      type: Property    
      x-ngsi:    
        model: https://schema.org/Text    
    platformName:    
      description: 'A mandatory text string used to declare the name of the platform'    
      type: Property    
      x-ngsi:    
        model: https://schema.org/Text    
    type:    
      description: 'NGSI-LD Entity Type. It must be equal to EOSatellitePlatform.'    
      enum:    
        - EOSatellitePlatform    
      type: Property    
  required:    
    - id    
    - type    
    - platformID    
    - platformName    
    - platformNSSDCA    
  type: object    
```  
</details>    





  "id": "urn:ngsi-ld:EOSatellitePlatform:154",  
  "type": "EOSatellitePlatform",  
  "platformID": "B",  
  "platformName": "Sentinel-1",  
  "platformNSSDCA": "2016-025A"  
}  
```  






  "id": "urn:ngsi-ld:EOSatellitePlatform:154",  
  "type": "EOSatellitePlatform",  
  "createdAt": "2020-03-13T15:42:00Z",  
  "modifiedAt": "2020-03-13T15:45:00Z",  
  "platformID": {  
    "type": "Property",  
    "value": "B"  
  },  
  "platformName": {  
    "type": "Property",  
    "value": "Sentinel-1"  
  },  
  "platformNSSDCA": {  
    "type": "Property",  
    "value": "2016-025A"  
  },  
  "@context": [  
    "https://schema.lab.fiware.org/ld/context"  
  ]  
}  
```  