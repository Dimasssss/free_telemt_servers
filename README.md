# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
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

# Server Metrics 2026-03-18 23:50:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 7308.0 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85231
telemt_connections_bad_total 8797
telemt_connections_current 654
telemt_connections_me_current 654
telemt_handshake_timeouts_total 934
telemt_upstream_connect_attempt_total 1350
telemt_upstream_connect_success_total 1327
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 1350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 713
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 921
telemt_me_reconnect_success_total 919
telemt_me_reader_eof_total 941
telemt_me_idle_close_by_peer_total 941
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 27518
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72237
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 387
telemt_desync_full_logged_total 126
telemt_desync_suppressed_total 261
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 169
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 918
telemt_me_writer_restored_same_endpoint_total 908
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 69481
telemt_user_connections_current{user="hello"} 654
telemt_user_octets_from_client{user="hello"} 699420012 (667.02 MB)
telemt_user_octets_to_client{user="hello"} 29645188168 (27.61 GB)
telemt_user_unique_ips_current{user="hello"} 264
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 7311.7 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190918
telemt_connections_bad_total 15590
telemt_connections_current 1539
telemt_connections_me_current 1539
telemt_handshake_timeouts_total 1631
telemt_upstream_connect_attempt_total 1400
telemt_upstream_connect_success_total 1367
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 1400
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 642
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 720
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 954
telemt_me_reconnect_success_total 953
telemt_me_reader_eof_total 993
telemt_me_idle_close_by_peer_total 993
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 59606
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163368
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 669
telemt_desync_full_logged_total 223
telemt_desync_suppressed_total 446
telemt_desync_frames_bucket_total{bucket="1_2"} 141
telemt_desync_frames_bucket_total{bucket="3_10"} 227
telemt_desync_frames_bucket_total{bucket="gt_10"} 301
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 971
telemt_me_writer_restored_same_endpoint_total 942
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 163445
telemt_user_connections_current{user="hello"} 1539
telemt_user_octets_from_client{user="hello"} 10329058920 (9.62 GB)
telemt_user_octets_to_client{user="hello"} 63697352056 (59.32 GB)
telemt_user_unique_ips_current{user="hello"} 614
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 7308.6 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148744
telemt_connections_bad_total 22386
telemt_connections_current 1073
telemt_connections_me_current 1073
telemt_handshake_timeouts_total 4282
telemt_upstream_connect_attempt_total 1419
telemt_upstream_connect_success_total 1419
telemt_upstream_connect_attempts_per_request{bucket="1"} 1419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 723
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 696
telemt_me_reconnect_attempts_total 1007
telemt_me_reconnect_success_total 1005
telemt_me_reader_eof_total 1037
telemt_me_idle_close_by_peer_total 1037
telemt_me_route_drop_no_conn_total 51322
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 118068
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 488
telemt_desync_full_logged_total 191
telemt_desync_suppressed_total 297
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 204
telemt_desync_frames_bucket_total{bucket="gt_10"} 192
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1017
telemt_me_writer_restored_same_endpoint_total 989
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 118070
telemt_user_connections_current{user="hello"} 1073
telemt_user_octets_from_client{user="hello"} 1578957292 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 72461645936 (67.49 GB)
telemt_user_unique_ips_current{user="hello"} 501
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 7362.1 (2h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160392
telemt_connections_bad_total 24973
telemt_connections_current 996
telemt_connections_me_current 996
telemt_handshake_timeouts_total 3210
telemt_upstream_connect_attempt_total 1369
telemt_upstream_connect_success_total 1369
telemt_upstream_connect_attempts_per_request{bucket="1"} 1369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 645
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 960
telemt_me_reconnect_success_total 957
telemt_me_reader_eof_total 987
telemt_me_idle_close_by_peer_total 987
telemt_me_route_drop_no_conn_total 62589
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 123322
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 295
telemt_desync_full_logged_total 112
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 120
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 970
telemt_me_writer_restored_same_endpoint_total 933
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 123250
telemt_user_connections_current{user="hello"} 996
telemt_user_octets_from_client{user="hello"} 1291403356 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 46711070996 (43.50 GB)
telemt_user_unique_ips_current{user="hello"} 413
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 7305.5 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163812
telemt_connections_bad_total 7372
telemt_connections_current 1173
telemt_connections_me_current 1173
telemt_handshake_timeouts_total 5531
telemt_upstream_connect_attempt_total 1340
telemt_upstream_connect_success_total 1332
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 662
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 919
telemt_me_reconnect_success_total 915
telemt_me_reader_eof_total 937
telemt_me_idle_close_by_peer_total 937
telemt_me_route_drop_no_conn_total 51773
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128585
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 551
telemt_desync_full_logged_total 221
telemt_desync_suppressed_total 330
telemt_desync_frames_bucket_total{bucket="1_2"} 131
telemt_desync_frames_bucket_total{bucket="3_10"} 191
telemt_desync_frames_bucket_total{bucket="gt_10"} 229
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 917
telemt_me_writer_restored_same_endpoint_total 891
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 128530
telemt_user_connections_current{user="hello"} 1173
telemt_user_octets_from_client{user="hello"} 1633059964 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 80222205064 (74.71 GB)
telemt_user_unique_ips_current{user="hello"} 530
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 7317.1 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38741
telemt_connections_bad_total 6931
telemt_connections_current 344
telemt_connections_me_current 344
telemt_handshake_timeouts_total 102
telemt_upstream_connect_attempt_total 2261
telemt_upstream_connect_success_total 2189
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 2261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1084
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_reconnect_attempts_total 3616
telemt_me_reconnect_success_total 1788
telemt_me_reader_eof_total 1848
telemt_me_idle_close_by_peer_total 1848
telemt_me_route_drop_no_conn_total 13552
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30794
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1824
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 1758
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 30795
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 384217344 (366.42 MB)
telemt_user_octets_to_client{user="hello"} 23555377108 (21.94 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 7307.8 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121556
telemt_connections_bad_total 15629
telemt_connections_current 1091
telemt_connections_me_current 1091
telemt_handshake_timeouts_total 4234
telemt_upstream_connect_attempt_total 1413
telemt_upstream_connect_success_total 1413
telemt_upstream_connect_attempts_per_request{bucket="1"} 1413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 671
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1000
telemt_me_reconnect_success_total 997
telemt_me_reader_eof_total 1029
telemt_me_idle_close_by_peer_total 1029
telemt_me_route_drop_no_conn_total 36816
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 99305
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 687
telemt_desync_full_logged_total 264
telemt_desync_suppressed_total 423
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 290
telemt_desync_frames_bucket_total{bucket="gt_10"} 281
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1009
telemt_me_writer_restored_same_endpoint_total 982
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 99330
telemt_user_connections_current{user="hello"} 1091
telemt_user_octets_from_client{user="hello"} 991650172 (945.71 MB)
telemt_user_octets_to_client{user="hello"} 52756830700 (49.13 GB)
telemt_user_unique_ips_current{user="hello"} 442
telemt_user_unique_ips_recent_window{user="hello"} 100
```