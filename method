 try {
                URL url=new URL("your url...");
                HttpURLConnection c=(java.net.HttpURLConnection)url.openConnection();
                c.setRequestMethod("GET");
                c.connect();
                InputStream is=c.getInputStream();
                BufferedReader br=new BufferedReader(new InputStreamReader(is));
                String line=null;

                while((line=br.readLine())!=null ){
                        String[] tokens=line.split(";");
                        //i dati sono nel vettore tokens[], li accedo con tokens[1],tokens[2] e così via... 
                }
                
            } catch (MalformedURLException e) {
                e.printStackTrace();//url malformato
                errore=true;
            } catch (IOException e) {
                errore=true;
                e.printStackTrace();//errore apertura connessione
            }
