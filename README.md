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

# Server Metrics 2026-03-16 14:32:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 3299.3 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40672
telemt_connections_bad_total 211
telemt_handshake_timeouts_total 1042
telemt_upstream_connect_attempt_total 618
telemt_upstream_connect_success_total 616
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 305
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 416
telemt_me_reconnect_success_total 412
telemt_me_reader_eof_total 394
telemt_me_idle_close_by_peer_total 394
telemt_me_route_drop_no_conn_total 11455
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37767
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 80
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 57
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 403
telemt_me_writer_restored_same_endpoint_total 410
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 37712
telemt_user_connections_current{user="hello"} 737
telemt_user_octets_from_client{user="hello"} 979442264 (934.07 MB)
telemt_user_octets_to_client{user="hello"} 24653082360 (22.96 GB)
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 863.7 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8945
telemt_connections_bad_total 280
telemt_handshake_timeouts_total 69
telemt_upstream_connect_attempt_total 8319
telemt_upstream_connect_success_total 8312
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 8318
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 941
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8310
telemt_user_connections_current{user="hello"} 550
telemt_user_octets_from_client{user="hello"} 118314396 (112.83 MB)
telemt_user_octets_to_client{user="hello"} 1348143093 (1.26 GB)
telemt_user_msgs_from_client{user="hello"} 135801
telemt_user_msgs_to_client{user="hello"} 423562
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 3412.9 (0h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16257
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 117
telemt_upstream_connect_attempt_total 2198
telemt_upstream_connect_success_total 2166
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 2198
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 849
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 30647
telemt_me_reconnect_success_total 993
telemt_me_reader_eof_total 1000
telemt_me_idle_close_by_peer_total 1000
telemt_me_route_drop_no_conn_total 4176
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14323
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 1023
telemt_me_refill_failed_total 926
telemt_me_writer_restored_same_endpoint_total 949
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 15279
telemt_user_connections_current{user="hello"} 279
telemt_user_octets_from_client{user="hello"} 184641866 (176.09 MB)
telemt_user_octets_to_client{user="hello"} 2674426642 (2.49 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 3548.5 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29107
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 503
telemt_upstream_connect_attempt_total 823
telemt_upstream_connect_success_total 819
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 373
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 1570
telemt_me_reconnect_success_total 595
telemt_me_reader_eof_total 604
telemt_me_idle_close_by_peer_total 604
telemt_me_route_drop_no_conn_total 8883
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27371
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 181
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 73
telemt_desync_frames_bucket_total{bucket="gt_10"} 74
telemt_me_writer_removed_unexpected_total 623
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 591
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 27351
telemt_user_connections_current{user="hello"} 468
telemt_user_octets_from_client{user="hello"} 653267780 (623.00 MB)
telemt_user_octets_to_client{user="hello"} 6380906972 (5.94 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 1008.9 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5018
telemt_connections_bad_total 1408
telemt_handshake_timeouts_total 11
telemt_upstream_connect_attempt_total 228
telemt_upstream_connect_success_total 224
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 141
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 124
telemt_me_reconnect_success_total 123
telemt_me_reader_eof_total 92
telemt_me_idle_close_by_peer_total 92
telemt_me_route_drop_no_conn_total 1129
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3365
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2
telemt_desync_full_logged_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_me_writer_removed_unexpected_total 109
telemt_me_writer_restored_same_endpoint_total 123
telemt_me_async_recovery_trigger_total 22
telemt_user_connections_total{user="hello"} 3351
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 201348708 (192.02 MB)
telemt_user_octets_to_client{user="hello"} 535750780 (510.93 MB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 3116.3 (0h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39981
telemt_connections_bad_total 1057
telemt_handshake_timeouts_total 469
telemt_upstream_connect_attempt_total 688
telemt_upstream_connect_success_total 688
telemt_upstream_connect_attempts_per_request{bucket="1"} 688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 314
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1539
telemt_me_reconnect_success_total 479
telemt_me_reader_eof_total 487
telemt_me_idle_close_by_peer_total 487
telemt_me_route_drop_no_conn_total 16235
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37308
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
telemt_me_writer_removed_unexpected_total 509
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 475
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 37185
telemt_user_connections_current{user="hello"} 824
telemt_user_octets_from_client{user="hello"} 983664648 (938.10 MB)
telemt_user_octets_to_client{user="hello"} 10172058988 (9.47 GB)
telemt_user_unique_ips_current{user="hello"} 284
telemt_user_unique_ips_recent_window{user="hello"} 110
```