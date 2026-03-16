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

# Server Metrics 2026-03-16 16:15:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 9429.7 (2h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102229
telemt_connections_bad_total 601
telemt_handshake_timeouts_total 3033
telemt_upstream_connect_attempt_total 2167
telemt_upstream_connect_success_total 2159
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 2167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1056
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1102
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2790
telemt_me_reconnect_success_total 1624
telemt_me_reader_eof_total 1673
telemt_me_idle_close_by_peer_total 1673
telemt_me_route_drop_no_conn_total 30226
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95062
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 497
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 397
telemt_desync_frames_bucket_total{bucket="1_2"} 217
telemt_desync_frames_bucket_total{bucket="3_10"} 173
telemt_desync_frames_bucket_total{bucket="gt_10"} 107
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1664
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 1622
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 94985
telemt_user_connections_current{user="hello"} 554
telemt_user_octets_from_client{user="hello"} 1790645684 (1.67 GB)
telemt_user_octets_to_client{user="hello"} 54099354632 (50.38 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 4208.8 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31383
telemt_connections_bad_total 398
telemt_handshake_timeouts_total 1210
telemt_upstream_connect_attempt_total 888
telemt_upstream_connect_success_total 880
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 478
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 639
telemt_me_reconnect_success_total 624
telemt_me_reader_eof_total 620
telemt_me_idle_close_by_peer_total 620
telemt_me_route_drop_no_conn_total 18375
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28764
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 638
telemt_me_writer_restored_same_endpoint_total 619
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 343
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 28737
telemt_user_connections_current{user="hello"} 397
telemt_user_octets_from_client{user="hello"} 245518100 (234.14 MB)
telemt_user_octets_to_client{user="hello"} 8212478896 (7.65 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 9542.7 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40927
telemt_connections_bad_total 41
telemt_handshake_timeouts_total 621
telemt_upstream_connect_attempt_total 2721
telemt_upstream_connect_success_total 2681
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 2721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1101
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_reconnect_attempts_total 38930
telemt_me_reconnect_success_total 1176
telemt_me_reader_eof_total 1437
telemt_me_idle_close_by_peer_total 1437
telemt_me_route_drop_no_conn_total 13632
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36938
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 42
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1462
telemt_me_refill_failed_total 1179
telemt_me_writer_restored_same_endpoint_total 1132
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 37886
telemt_user_connections_current{user="hello"} 274
telemt_user_octets_from_client{user="hello"} 414309766 (395.12 MB)
telemt_user_octets_to_client{user="hello"} 7094976150 (6.61 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 9678.9 (2h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75085
telemt_connections_bad_total 146
telemt_handshake_timeouts_total 1063
telemt_upstream_connect_attempt_total 2061
telemt_upstream_connect_success_total 2044
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 2061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1050
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 7825
telemt_me_reconnect_success_total 1485
telemt_me_reader_eof_total 1679
telemt_me_idle_close_by_peer_total 1679
telemt_me_route_drop_no_conn_total 25004
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71047
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 436
telemt_desync_full_logged_total 106
telemt_desync_suppressed_total 330
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 183
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1698
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 1481
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 213
telemt_user_connections_total{user="hello"} 71026
telemt_user_connections_current{user="hello"} 540
telemt_user_octets_from_client{user="hello"} 1085329988 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 17672861180 (16.46 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 7139.6 (1h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39709
telemt_connections_bad_total 14478
telemt_handshake_timeouts_total 295
telemt_upstream_connect_attempt_total 1760
telemt_upstream_connect_success_total 1736
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 1760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1043
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 2006
telemt_me_reconnect_success_total 1349
telemt_me_reader_eof_total 1389
telemt_me_idle_close_by_peer_total 1389
telemt_me_route_drop_no_conn_total 9469
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23685
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1390
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 1349
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 23664
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 1483304000 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 10780574328 (10.04 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 9246.7 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107534
telemt_connections_bad_total 1203
telemt_handshake_timeouts_total 2133
telemt_upstream_connect_attempt_total 1974
telemt_upstream_connect_success_total 1974
telemt_upstream_connect_attempts_per_request{bucket="1"} 1974
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1005
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 3822
telemt_me_reconnect_success_total 1440
telemt_me_reader_eof_total 1527
telemt_me_idle_close_by_peer_total 1527
telemt_me_route_drop_no_conn_total 49805
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100639
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1526
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1436
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 100369
telemt_user_connections_current{user="hello"} 739
telemt_user_octets_from_client{user="hello"} 2060068016 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 32742829928 (30.49 GB)
telemt_user_unique_ips_current{user="hello"} 264
telemt_user_unique_ips_recent_window{user="hello"} 84
```