# 3D-Scanning
1. We first tried using a 3D scanner, and the first problem we found was that it requires a LiDAR device, which not all phones or tablets have.
2. After finding the right device, we scanned objects in our dorm room, but instead of getting a single object as we wanted, the scan captured the entire room.
3. So we borrowed a 3D scanner from our teacher. We used Revopoint paired with a dual-axis turntable.
![revopoint](https://github.com/user-attachments/assets/42ddf2e6-ef6f-4996-a255-9728214d6a0a)
![dual-axis turntable](https://github.com/user-attachments/assets/cb982777-b46d-4b98-9db2-c49379da140a)
![advanced mode](https://github.com/user-attachments/assets/e664fe34-496c-49f0-96f9-5e09e0e5c98d)


4. At first, we scanned a pen, but since it was lying flat, it was hard to separate it from the tray.
5. Then we tried scanning a thermos cup, but it was too big, so we had to rotate the 3D scanner 90 degrees to capture it.
![638cc8ca1772eb9513280d6b9388dbcd](https://github.com/user-attachments/assets/66420c37-dc1e-492f-ba7b-f7d0f1e10870)


6. We also found that the 3D scanner couldn’t clearly recognize the strap of the thermos, and it ended up generating multiple straps.
<img width="1280" height="611" alt="failure case" src="https://github.com/user-attachments/assets/d0cabc73-b4da-40e5-93a2-493b8ef1cbfc" />

7. Finally, we removed the strap and got a relatively good 3D model. However, the top and bottom that weren’t scanned were left open, turning it into an unsealed cavity, and we weren’t able to fix this problem.
![cd30a7d3b93d49abd76b995a36cbd83d](https://github.com/user-attachments/assets/b018f8b4-4afd-4466-b290-f3556f311b7e)
![a5c2acab71f30ff4042a6b8dba7d47b4](https://github.com/user-attachments/assets/f490f229-a2c7-4611-8f5d-d3f0a633b607)


p.s.Later, we needed to 3D print it, so I used a meshmixer to fill this hole. The stl file of our scanned model can be viewed in the file
