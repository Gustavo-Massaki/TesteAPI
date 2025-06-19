import requests

url = "https://ubhkfmoakvdmzyvommtx.supabase.co/rest/v1/users"

api_key = "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6InViaGtmbW9ha3ZkbXp5dm9tbXR4Iiwicm9sZSI6ImFub24iLCJpYXQiOjE3NTAyOTA5MTQsImV4cCI6MjA2NTg2NjkxNH0.ZlumTyQrCSRESiwCGPf-n_kSp9lF4OKttiArIuv3Iaw"

headers = {
    "apikey": api_key,
    "Authorization": f"Bearer {api_key}",
    "Content-Type": "Aplication/json"
}

response = requests.get(url, headers=headers)

if response.status_code == 200:
    dados = response.json()
    print(dados)
else:
    print(f"Erro {response.status_code}: {response.text}")
