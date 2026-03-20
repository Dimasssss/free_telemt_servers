# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

**Принимаю донаты криптой для добавления и продления серверов:**  
- TON: UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-20 07:10:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 49980.1 (13h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1033460
telemt_connections_bad_total 62338
telemt_connections_current 1740
telemt_connections_me_current 1740
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 26764
telemt_upstream_connect_attempt_total 9668
telemt_upstream_connect_success_total 9560
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 9668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4327
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 6008
telemt_me_reconnect_success_total 5963
telemt_me_reader_eof_total 6310
telemt_me_idle_close_by_peer_total 6309
telemt_me_route_drop_no_conn_total 297833
telemt_me_route_drop_channel_closed_total 120
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 846121
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4323
telemt_desync_full_logged_total 1561
telemt_desync_suppressed_total 2762
telemt_desync_frames_bucket_total{bucket="1_2"} 866
telemt_desync_frames_bucket_total{bucket="3_10"} 1674
telemt_desync_frames_bucket_total{bucket="gt_10"} 1783
telemt_pool_swap_total 53
telemt_me_writer_close_signal_drop_total 62
telemt_me_writer_removed_unexpected_total 6028
telemt_me_writer_restored_same_endpoint_total 5950
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 845552
telemt_user_connections_current{user="hello"} 1740
telemt_user_octets_from_client{user="hello"} 34853789804 (32.46 GB)
telemt_user_octets_to_client{user="hello"} 291949990025 (271.90 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 593
telemt_user_unique_ips_recent_window{user="hello"} 278
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 66435.8 (18h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4691660
telemt_connections_bad_total 432764
telemt_connections_current 7061
telemt_connections_me_current 7061
telemt_handshake_timeouts_total 101154
telemt_upstream_connect_attempt_total 12358
telemt_upstream_connect_success_total 12130
telemt_upstream_connect_fail_total 228
telemt_upstream_connect_attempts_per_request{bucket="1"} 12358
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5235
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 228
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 11874
telemt_me_reconnect_success_total 7615
telemt_me_reader_eof_total 8149
telemt_me_idle_close_by_peer_total 8148
telemt_me_route_drop_no_conn_total 2503049
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3853915
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14723
telemt_desync_full_logged_total 4869
telemt_desync_suppressed_total 9854
telemt_desync_frames_bucket_total{bucket="1_2"} 2911
telemt_desync_frames_bucket_total{bucket="3_10"} 5742
telemt_desync_frames_bucket_total{bucket="gt_10"} 6070
telemt_pool_swap_total 59
telemt_pool_stale_pick_total 8
telemt_me_writer_close_signal_drop_total 92
telemt_me_writer_removed_unexpected_total 7850
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7560
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 235
telemt_user_connections_total{user="hello"} 3853652
telemt_user_connections_current{user="hello"} 7061
telemt_user_octets_from_client{user="hello"} 53502153142 (49.83 GB)
telemt_user_octets_to_client{user="hello"} 1340419115670 (1.22 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1857
telemt_user_unique_ips_recent_window{user="hello"} 1243
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 66414.6 (18h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4141886
telemt_connections_bad_total 537242
telemt_connections_current 4003
telemt_connections_me_current 4003
telemt_handshake_timeouts_total 64226
telemt_upstream_connect_attempt_total 12225
telemt_upstream_connect_success_total 12120
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 12225
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5582
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 3085
telemt_me_reconnect_attempts_total 8325
telemt_me_reconnect_success_total 7364
telemt_me_reader_eof_total 7704
telemt_me_idle_close_by_peer_total 7699
telemt_me_route_drop_no_conn_total 2751624
telemt_me_route_drop_channel_closed_total 260
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2971502
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 179
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10409
telemt_desync_full_logged_total 3258
telemt_desync_suppressed_total 7151
telemt_desync_frames_bucket_total{bucket="1_2"} 2518
telemt_desync_frames_bucket_total{bucket="3_10"} 3976
telemt_desync_frames_bucket_total{bucket="gt_10"} 3915
telemt_pool_swap_total 65
telemt_me_writer_close_signal_drop_total 316
telemt_me_writer_removed_unexpected_total 7460
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 7363
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 2977892
telemt_user_connections_current{user="hello"} 4003
telemt_user_octets_from_client{user="hello"} 41557105334 (38.70 GB)
telemt_user_octets_to_client{user="hello"} 1111638257732 (1.01 TB)
telemt_user_msgs_from_client{user="hello"} 2664
telemt_user_msgs_to_client{user="hello"} 1842
telemt_user_unique_ips_current{user="hello"} 1325
telemt_user_unique_ips_recent_window{user="hello"} 589
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 66401.8 (18h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4491962
telemt_connections_bad_total 284844
telemt_connections_current 5254
telemt_connections_me_current 5254
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 63690
telemt_upstream_connect_attempt_total 67997
telemt_upstream_connect_success_total 63261
telemt_upstream_connect_fail_total 4736
telemt_upstream_connect_attempts_per_request{bucket="1"} 67997
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9851
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 712
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4736
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 10558
telemt_me_reconnect_success_total 7573
telemt_me_reader_eof_total 7914
telemt_me_idle_close_by_peer_total 7913
telemt_me_route_drop_no_conn_total 4990685
telemt_me_route_drop_channel_closed_total 76
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3763994
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12564
telemt_desync_full_logged_total 3686
telemt_desync_suppressed_total 8878
telemt_desync_frames_bucket_total{bucket="1_2"} 2853
telemt_desync_frames_bucket_total{bucket="3_10"} 4945
telemt_desync_frames_bucket_total{bucket="gt_10"} 4766
telemt_pool_swap_total 54
telemt_me_writer_close_signal_drop_total 677
telemt_me_writer_removed_unexpected_total 8301
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7569
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 410
telemt_me_writer_removed_unexpected_minus_restored_total 728
telemt_user_connections_total{user="hello"} 3815242
telemt_user_connections_current{user="hello"} 5254
telemt_user_octets_from_client{user="hello"} 45981090136 (42.82 GB)
telemt_user_octets_to_client{user="hello"} 848247401227 (789.99 GB)
telemt_user_msgs_from_client{user="hello"} 260491
telemt_user_msgs_to_client{user="hello"} 1782062
telemt_user_unique_ips_current{user="hello"} 1457
telemt_user_unique_ips_recent_window{user="hello"} 982
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 3984.9 (1h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 638756
telemt_connections_bad_total 60676
telemt_connections_current 5340
telemt_connections_me_current 5340
telemt_handshake_timeouts_total 11503
telemt_upstream_connect_attempt_total 638
telemt_upstream_connect_success_total 635
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 638
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 292
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 390
telemt_me_reconnect_success_total 388
telemt_me_reader_eof_total 372
telemt_me_idle_close_by_peer_total 372
telemt_me_route_drop_no_conn_total 755132
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 527860
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1453
telemt_desync_full_logged_total 447
telemt_desync_suppressed_total 1006
telemt_desync_frames_bucket_total{bucket="1_2"} 282
telemt_desync_frames_bucket_total{bucket="3_10"} 592
telemt_desync_frames_bucket_total{bucket="gt_10"} 579
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 25
telemt_me_writer_removed_unexpected_total 381
telemt_me_writer_restored_same_endpoint_total 358
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_user_connections_total{user="hello"} 527812
telemt_user_connections_current{user="hello"} 5340
telemt_user_octets_from_client{user="hello"} 7365947572 (6.86 GB)
telemt_user_octets_to_client{user="hello"} 100763375560 (93.84 GB)
telemt_user_unique_ips_current{user="hello"} 1612
telemt_user_unique_ips_recent_window{user="hello"} 1063
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 3920.5 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63118
telemt_connections_bad_total 11477
telemt_connections_current 656
telemt_connections_me_current 656
telemt_handshake_timeouts_total 768
telemt_upstream_connect_attempt_total 770
telemt_upstream_connect_success_total 763
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 770
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 371
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 520
telemt_me_reconnect_success_total 517
telemt_me_reader_eof_total 517
telemt_me_idle_close_by_peer_total 517
telemt_me_route_drop_no_conn_total 34250
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61194
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 231
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 24
telemt_me_writer_removed_unexpected_total 518
telemt_me_writer_restored_same_endpoint_total 509
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 48207
telemt_user_connections_current{user="hello"} 657
telemt_user_octets_from_client{user="hello"} 528887632 (504.39 MB)
telemt_user_octets_to_client{user="hello"} 19136201304 (17.82 GB)
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 66366.4 (18h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2927853
telemt_connections_bad_total 183518
telemt_connections_current 4650
telemt_connections_me_current 4650
telemt_handshake_timeouts_total 53383
telemt_upstream_connect_attempt_total 11696
telemt_upstream_connect_success_total 11622
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 11696
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5295
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 8387
telemt_me_reconnect_success_total 8332
telemt_me_reader_eof_total 8809
telemt_me_idle_close_by_peer_total 8809
telemt_me_route_drop_no_conn_total 1000107
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2459819
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12242
telemt_desync_full_logged_total 4003
telemt_desync_suppressed_total 8239
telemt_desync_frames_bucket_total{bucket="1_2"} 2466
telemt_desync_frames_bucket_total{bucket="3_10"} 4305
telemt_desync_frames_bucket_total{bucket="gt_10"} 5471
telemt_pool_swap_total 68
telemt_me_writer_close_signal_drop_total 49
telemt_me_writer_removed_unexpected_total 8450
telemt_me_writer_restored_same_endpoint_total 8315
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 2458641
telemt_user_connections_current{user="hello"} 4650
telemt_user_octets_from_client{user="hello"} 53390674520 (49.72 GB)
telemt_user_octets_to_client{user="hello"} 1286538182120 (1.17 TB)
telemt_user_unique_ips_current{user="hello"} 1498
telemt_user_unique_ips_recent_window{user="hello"} 635
```