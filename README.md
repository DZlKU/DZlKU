<div align="center">

  <!-- BANNER / WANTED POSTER HEADER -->
  <br />
  <h1>🤠 SEBASTIAN BEDNARZ 🪓</h1>
  <h3><code>C++ & UNREAL ENGINE GAMEPLAY ENGINEER</code></h3>

  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExM3ZkYWtrN2Rnb3F4czJ4OXVpeXZsdTF2ZXd1YjlndXRvczl2Z2p3diZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/ECoYUBS0V3GS4/giphy.gif" width="100%" max-width="700px" style="border-radius: 8px;" alt="Red Dead / God of War Vibe Banner" />

  <br /><br />

  <table border="0" width="100%">
    <tr>
      <td align="center" bgcolor="#1e293b" style="padding: 12px; border-radius: 6px;">
        <b>🎯 TARGET:</b> US & EU Remote B2B Contracts &nbsp;|&nbsp;
        <b>📍 LOCATION:</b> Poland (CET / UTC+1) &nbsp;|&nbsp;
        <b>⚙️ ENGINE:</b> Unreal Engine 4.27 / UE5
      </td>
    </tr>
  </table>

</div>

<hr />

<!-- UKŁAD DWUKOLUMNOWY (TABLE-BASED GRID) -->
<table border="0" width="100%" cellspacing="0" cellpadding="10">
  <tr valign="top">
    
    <!-- LEWA KOLUMNA: THE JOURNAL (ABOUT ME) -->
    <td width="50%">
      <h3>📜 THE JOURNAL</h3>
      <p>
        <i>"In the realm of code, every byte is a battlefield. I forge high-performance gameplay systems and multiplayer netcode in Unreal Engine."</i>
      </p>
      <ul>
        <li><b>Primary Focus:</b> Modular C++ Gameplay Architecture & Memory Optimization.</li>
        <li><b>Specialization:</b> Gameplay Ability System (GAS) & Network Replication (RPCs).</li>
        <li><b>Workflow:</b> Clean Code, Smart Pointers, Async Task Graph, Unreal Insights.</li>
        <li><b>Availability:</b> Open for US East/West Coast time zone overlap.</li>
      </ul>
    </td>

    <!-- PRAWA KOLUMNA: WEAPONS & ARSENAL (TECH STACK) -->
    <td width="50%">
      <h3>⚔️ EQUIPMENT & ARSENAL</h3>
      <table border="1" width="100%" cellpadding="6" style="border-collapse: collapse; border-color: #334155;">
        <tr>
          <td bgcolor="#0f172a"><b>Languages</b></td>
          <td>C++17 / C++20, HLSL, Python</td>
        </tr>
        <tr>
          <td bgcolor="#0f172a"><b>Engine</b></td>
          <td>Unreal Engine 4.27 / 5, GAS, Netcode</td>
        </tr>
        <tr>
          <td bgcolor="#0f172a"><b>Profiling</b></td>
          <td>Unreal Insights, Visual Studio, RenderDoc</td>
        </tr>
        <tr>
          <td bgcolor="#0f172a"><b>Tools</b></td>
          <td>Git / Git LFS, Perforce, JIRA, Agile</td>
        </tr>
      </table>
    </td>

  </tr>
</table>

<hr />

<!-- QUEST LOG: MIEJSCE NA GIF-Y I POKAZ SYSTEMÓW -->
<div align="center">
  <h2>🗡️ QUEST LOG & SHOWCASE</h2>
  <p><i>Real-time C++ systems running live in Unreal Engine</i></p>
</div>

<br />

<table border="0" width="100%" cellspacing="0" cellpadding="10">
  <tr valign="top">
    
    <!-- CARD 1: MULTIPLAYER NETCODE -->
    <td width="50%" align="center">
      <table border="1" width="100%" cellpadding="10" style="border-collapse: collapse; border-color: #d97706;">
        <tr>
          <td bgcolor="#1e293b" align="center">
            <h4>🔥 QUEST 1: Networked Ability & Inventory Framework</h4>
          </td>
        </tr>
        <tr>
          <td align="center">
            <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExazl5bmlzeXVwYW1vZnl5NWYxcTFkZzI5aGNmbW5qZnhpdTNwZTFvaCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/3lF6edWB83PzC/giphy.gif" width="100%" style="border-radius: 4px;" alt="Netcode Demo" />
            <br /><br />
            <p align="left">
              • <b>Architecture:</b> Custom Replicated Component in C++.<br />
              • <b>Features:</b> Client-side prediction, fast array serialization, GAS attributes.<br />
              • <b>Engine:</b> Unreal Engine 4.27
            </p>
          </td>
        </tr>
      </table>
    </td>

    <!-- CARD 2: GAS COMBAT SYSTEM -->
    <td width="50%" align="center">
      <table border="1" width="100%" cellpadding="10" style="border-collapse: collapse; border-color: #d97706;">
        <tr>
          <td bgcolor="#1e293b" align="center">
            <h4>🪓 QUEST 2: GAS Attribute & Combat Pipeline</h4>
          </td>
        </tr>
        <tr>
          <td align="center">
            <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExM3ZkYWtrN2Rnb3F4czJ4OXVpeXZsdTF2ZXd1YjlndXRvczl2Z2p3diZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/ECoYUBS0V3GS4/giphy.gif" width="100%" style="border-radius: 4px;" alt="GAS Combat Demo" />
            <br /><br />
            <p align="left">
              • <b>Architecture:</b> Custom <code>UAttributeSet</code> & Gameplay Effects.<br />
              • <b>Features:</b> Dynamic damage calculation, stamina drain, tag system.<br />
              • <b>Engine:</b> Unreal Engine 4.27
            </p>
          </td>
        </tr>
      </table>
    </td>

  </tr>
</table>

<br /><hr />

<!-- EXPANDABLE CODE SNIPPET (DETAILS / SUMMARY) -->
<details>
  <summary><b>📜 CLICK TO INSPECT ARCHITECTURE CODE SAMPLE (C++)</b></summary>
  <br />
  <p>Example snippet of a replicated item component interface written in clean C++ for Unreal Engine 4.27:</p>

```cpp
// Replicated Component Header Sample
#pragma once

#include "CoreMinimal.h"
#include "Components/ActorComponent.h"
#include "UObject/CoreNet.h"
#include "MyInventoryComponent.generated.h"

UCLASS(ClassGroup=(Custom), meta=(BlueprintSpawnableComponent))
class MYPROJECT_API UMyInventoryComponent : public UActorComponent
{
    GENERATED_BODY()

public:	
    UMyInventoryComponent();

protected:
    virtual void GetLifetimeReplicatedProps(TArray<FLifetimeProperty>& OutLifetimeProps) const override;

    UPROPERTY(ReplicatedUsing = OnRep_InventoryUpdated, BlueprintReadOnly, Category = "Inventory")
    TArray<FName> InventoryItems;

    UFUNCTION()
    void OnRep_InventoryUpdated();
};
