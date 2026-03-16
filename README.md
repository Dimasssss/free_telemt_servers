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

# Server Metrics 2026-03-16 14:37:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 3606.3 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43925
telemt_connections_bad_total 258
telemt_handshake_timeouts_total 1110
telemt_upstream_connect_attempt_total 643
telemt_upstream_connect_success_total 641
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 643
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 318
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 441
telemt_me_reconnect_success_total 436
telemt_me_reader_eof_total 418
telemt_me_idle_close_by_peer_total 418
telemt_me_route_drop_no_conn_total 12491
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40761
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 91
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 64
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 427
telemt_me_writer_restored_same_endpoint_total 434
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 40706
telemt_user_connections_current{user="hello"} 821
telemt_user_octets_from_client{user="hello"} 1000006904 (953.68 MB)
telemt_user_octets_to_client{user="hello"} 26095017688 (24.30 GB)
telemt_user_unique_ips_current{user="hello"} 228
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 1170.0 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11996
telemt_connections_bad_total 281
telemt_handshake_timeouts_total 80
telemt_upstream_connect_attempt_total 11227
telemt_upstream_connect_success_total 11218
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 11226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9379
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 591
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1248
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11216
telemt_user_connections_current{user="hello"} 525
telemt_user_octets_from_client{user="hello"} 163313061 (155.75 MB)
telemt_user_octets_to_client{user="hello"} 1885010748 (1.76 GB)
telemt_user_msgs_from_client{user="hello"} 183621
telemt_user_msgs_to_client{user="hello"} 578408
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 3719.0 (1h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17483
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 129
telemt_upstream_connect_attempt_total 2238
telemt_upstream_connect_success_total 2204
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 2238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 861
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_reconnect_attempts_total 30656
telemt_me_reconnect_success_total 1002
telemt_me_reader_eof_total 1009
telemt_me_idle_close_by_peer_total 1009
telemt_me_route_drop_no_conn_total 4542
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15505
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 1032
telemt_me_refill_failed_total 926
telemt_me_writer_restored_same_endpoint_total 958
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 16461
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 196851890 (187.73 MB)
telemt_user_octets_to_client{user="hello"} 2822700638 (2.63 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 3855.1 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31461
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 523
telemt_upstream_connect_attempt_total 914
telemt_upstream_connect_success_total 909
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 913
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 420
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 2959
telemt_me_reconnect_success_total 639
telemt_me_reader_eof_total 690
telemt_me_idle_close_by_peer_total 690
telemt_me_route_drop_no_conn_total 9718
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29647
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 195
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 145
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 76
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_me_writer_removed_unexpected_total 710
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 635
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 29628
telemt_user_connections_current{user="hello"} 482
telemt_user_octets_from_client{user="hello"} 673410756 (642.21 MB)
telemt_user_octets_to_client{user="hello"} 6843389804 (6.37 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 1315.6 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6563
telemt_connections_bad_total 2000
telemt_handshake_timeouts_total 25
telemt_upstream_connect_attempt_total 305
telemt_upstream_connect_success_total 300
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 184
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 193
telemt_me_reconnect_success_total 189
telemt_me_reader_eof_total 164
telemt_me_idle_close_by_peer_total 164
telemt_me_route_drop_no_conn_total 1412
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4288
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 177
telemt_me_writer_restored_same_endpoint_total 189
telemt_me_async_recovery_trigger_total 22
telemt_user_connections_total{user="hello"} 4274
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 206040008 (196.50 MB)
telemt_user_octets_to_client{user="hello"} 713279532 (680.24 MB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 3423.1 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44136
telemt_connections_bad_total 1057
telemt_handshake_timeouts_total 780
telemt_upstream_connect_attempt_total 734
telemt_upstream_connect_success_total 734
telemt_upstream_connect_attempts_per_request{bucket="1"} 734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1585
telemt_me_reconnect_success_total 526
telemt_me_reader_eof_total 533
telemt_me_idle_close_by_peer_total 533
telemt_me_route_drop_no_conn_total 18033
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41100
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_me_writer_removed_unexpected_total 555
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 522
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 40971
telemt_user_connections_current{user="hello"} 716
telemt_user_octets_from_client{user="hello"} 1041615940 (993.36 MB)
telemt_user_octets_to_client{user="hello"} 11174897760 (10.41 GB)
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 108
```