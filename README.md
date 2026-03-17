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

# Server Metrics 2026-03-17 03:16:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 30641.4 (8h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159549
telemt_connections_bad_total 2379
telemt_handshake_timeouts_total 5517
telemt_upstream_connect_attempt_total 6568
telemt_upstream_connect_success_total 6529
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 6568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3582
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5017
telemt_me_reconnect_success_total 5001
telemt_me_reader_eof_total 5317
telemt_me_idle_close_by_peer_total 5317
telemt_me_route_drop_no_conn_total 51172
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 144792
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 848
telemt_desync_full_logged_total 293
telemt_desync_suppressed_total 555
telemt_desync_frames_bucket_total{bucket="1_2"} 195
telemt_desync_frames_bucket_total{bucket="3_10"} 431
telemt_desync_frames_bucket_total{bucket="gt_10"} 222
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 5045
telemt_me_writer_restored_same_endpoint_total 4980
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 144602
telemt_user_connections_current{user="hello"} 390
telemt_user_octets_from_client{user="hello"} 1946995116 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 65470203232 (60.97 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 30892.5 (8h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89474
telemt_connections_bad_total 1393
telemt_handshake_timeouts_total 3125
telemt_upstream_connect_attempt_total 8552
telemt_upstream_connect_success_total 8437
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 8552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4862
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_reconnect_attempts_total 8055
telemt_me_reconnect_success_total 6887
telemt_me_reader_eof_total 7276
telemt_me_idle_close_by_peer_total 7276
telemt_me_route_drop_no_conn_total 37880
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81301
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 187
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 125
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6992
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 6871
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 81245
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 1159939692 (1.08 GB)
telemt_user_octets_to_client{user="hello"} 37494202596 (34.92 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 30669.3 (8h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58273
telemt_connections_bad_total 787
telemt_handshake_timeouts_total 1968
telemt_upstream_connect_attempt_total 8233
telemt_upstream_connect_success_total 8186
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 8233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3616
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4510
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 6669
telemt_me_reconnect_success_total 6631
telemt_me_reader_eof_total 7089
telemt_me_idle_close_by_peer_total 7089
telemt_me_route_drop_no_conn_total 18426
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49254
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 29
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 6717
telemt_me_writer_restored_same_endpoint_total 6620
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 49238
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 5575850860 (5.19 GB)
telemt_user_octets_to_client{user="hello"} 17880518788 (16.65 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 30728.0 (8h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91006
telemt_connections_bad_total 3378
telemt_handshake_timeouts_total 1305
telemt_upstream_connect_attempt_total 7126
telemt_upstream_connect_success_total 7063
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 7126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3701
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_reconnect_attempts_total 5533
telemt_me_reconnect_success_total 5495
telemt_me_reader_eof_total 5838
telemt_me_idle_close_by_peer_total 5838
telemt_me_route_drop_no_conn_total 31357
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83770
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 153
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 106
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 5572
telemt_me_writer_restored_same_endpoint_total 5488
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 83754
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 956564144 (912.25 MB)
telemt_user_octets_to_client{user="hello"} 39459306700 (36.75 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 30700.0 (8h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69233
telemt_connections_bad_total 16182
telemt_handshake_timeouts_total 1230
telemt_upstream_connect_attempt_total 9016
telemt_upstream_connect_success_total 8896
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 9016
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4747
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_reconnect_attempts_total 9589
telemt_me_reconnect_success_total 7340
telemt_me_reader_eof_total 7743
telemt_me_idle_close_by_peer_total 7743
telemt_me_route_drop_no_conn_total 19910
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49863
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 7521
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 7332
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 49859
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 584713888 (557.63 MB)
telemt_user_octets_to_client{user="hello"} 20365781940 (18.97 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 30860.9 (8h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175403
telemt_connections_bad_total 14841
telemt_handshake_timeouts_total 1106
telemt_upstream_connect_attempt_total 6435
telemt_upstream_connect_success_total 6399
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 6435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3360
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_reconnect_attempts_total 4865
telemt_me_reconnect_success_total 4849
telemt_me_reader_eof_total 5201
telemt_me_idle_close_by_peer_total 5201
telemt_me_route_drop_no_conn_total 180992
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 231564
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 58
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 4918
telemt_me_writer_restored_same_endpoint_total 4839
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 153817
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 2429059036 (2.26 GB)
telemt_user_octets_to_client{user="hello"} 122873014324 (114.43 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 18867.5 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 9483
telemt_upstream_connect_success_total 9483
telemt_upstream_connect_attempts_per_request{bucket="1"} 9483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3985
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 8548
telemt_me_reconnect_success_total 8502
telemt_me_reader_eof_total 9317
telemt_me_idle_close_by_peer_total 9317
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 8588
telemt_me_writer_restored_same_endpoint_total 8502
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 157473040 (150.18 MB)
telemt_user_octets_to_client{user="hello"} 23027108 (21.96 MB)
```