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

# Server Metrics 2026-03-16 15:03:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 5140.7 (1h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59773
telemt_connections_bad_total 355
telemt_handshake_timeouts_total 1422
telemt_upstream_connect_attempt_total 1021
telemt_upstream_connect_success_total 1019
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 1021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 535
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 727
telemt_me_reconnect_success_total 720
telemt_me_reader_eof_total 709
telemt_me_idle_close_by_peer_total 709
telemt_me_route_drop_no_conn_total 17198
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55622
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 252
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 199
telemt_desync_frames_bucket_total{bucket="1_2"} 100
telemt_desync_frames_bucket_total{bucket="3_10"} 106
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 712
telemt_me_writer_restored_same_endpoint_total 718
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 55557
telemt_user_connections_current{user="hello"} 662
telemt_user_octets_from_client{user="hello"} 1210616884 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 33649569948 (31.34 GB)
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 2705.6 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27366
telemt_connections_bad_total 282
telemt_handshake_timeouts_total 226
telemt_upstream_connect_attempt_total 26012
telemt_upstream_connect_success_total 25989
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 26009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1385
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2837
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25987
telemt_user_connections_current{user="hello"} 526
telemt_user_octets_from_client{user="hello"} 307523133 (293.28 MB)
telemt_user_octets_to_client{user="hello"} 5720569957 (5.33 GB)
telemt_user_msgs_from_client{user="hello"} 394108
telemt_user_msgs_to_client{user="hello"} 1628717
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 5253.4 (1h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24567
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 254
telemt_upstream_connect_attempt_total 2353
telemt_upstream_connect_success_total 2318
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 2353
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 925
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_reconnect_attempts_total 33428
telemt_me_reconnect_success_total 1054
telemt_me_reader_eof_total 1146
telemt_me_idle_close_by_peer_total 1146
telemt_me_route_drop_no_conn_total 6596
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21571
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_me_writer_removed_unexpected_total 1169
telemt_me_refill_failed_total 1011
telemt_me_writer_restored_same_endpoint_total 1010
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 22524
telemt_user_connections_current{user="hello"} 294
telemt_user_octets_from_client{user="hello"} 237484078 (226.48 MB)
telemt_user_octets_to_client{user="hello"} 3662438510 (3.41 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 5389.8 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42938
telemt_connections_bad_total 28
telemt_handshake_timeouts_total 726
telemt_upstream_connect_attempt_total 1150
telemt_upstream_connect_success_total 1143
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 576
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 554
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 4490
telemt_me_reconnect_success_total 823
telemt_me_reader_eof_total 912
telemt_me_idle_close_by_peer_total 912
telemt_me_route_drop_no_conn_total 14323
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40522
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 229
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 171
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_me_writer_removed_unexpected_total 935
telemt_me_refill_failed_total 114
telemt_me_writer_restored_same_endpoint_total 819
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 40502
telemt_user_connections_current{user="hello"} 421
telemt_user_octets_from_client{user="hello"} 784602680 (748.26 MB)
telemt_user_octets_to_client{user="hello"} 9445885624 (8.80 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 2850.5 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15574
telemt_connections_bad_total 5485
telemt_handshake_timeouts_total 63
telemt_upstream_connect_attempt_total 692
telemt_upstream_connect_success_total 683
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 251
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 401
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 487
telemt_me_reconnect_success_total 480
telemt_me_reader_eof_total 467
telemt_me_idle_close_by_peer_total 467
telemt_me_route_drop_no_conn_total 3173
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9507
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 484
telemt_me_writer_restored_same_endpoint_total 480
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 9491
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 247937552 (236.45 MB)
telemt_user_octets_to_client{user="hello"} 1619293536 (1.51 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 4957.6 (1h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60944
telemt_connections_bad_total 1099
telemt_handshake_timeouts_total 1263
telemt_upstream_connect_attempt_total 1052
telemt_upstream_connect_success_total 1052
telemt_upstream_connect_attempts_per_request{bucket="1"} 1052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 530
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 3127
telemt_me_reconnect_success_total 755
telemt_me_reader_eof_total 817
telemt_me_idle_close_by_peer_total 817
telemt_me_route_drop_no_conn_total 25603
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56899
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 1
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
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 829
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 751
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 56765
telemt_user_connections_current{user="hello"} 753
telemt_user_octets_from_client{user="hello"} 1265924924 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 15822134624 (14.74 GB)
telemt_user_unique_ips_current{user="hello"} 258
telemt_user_unique_ips_recent_window{user="hello"} 106
```