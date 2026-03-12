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

# Server Metrics 2026-03-12 09:49:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 8161.8 (2h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42896
telemt_connections_bad_total 33
telemt_handshake_timeouts_total 2084
telemt_upstream_connect_attempt_total 2023
telemt_upstream_connect_success_total 2015
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 2023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1105
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1582
telemt_me_reconnect_success_total 1572
telemt_me_reader_eof_total 1596
telemt_me_idle_close_by_peer_total 1596
telemt_me_route_drop_no_conn_total 11417
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38354
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 122
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1576
telemt_me_writer_restored_same_endpoint_total 1556
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 38331
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 619849840 (591.13 MB)
telemt_user_octets_to_client{user="hello"} 10845811420 (10.10 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 8054.9 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17674
telemt_connections_bad_total 126
telemt_handshake_timeouts_total 174
telemt_upstream_connect_attempt_total 2865
telemt_upstream_connect_success_total 2813
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 2865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1853
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 57
telemt_me_reconnect_attempts_total 5187
telemt_me_reconnect_success_total 2397
telemt_me_reader_eof_total 2510
telemt_me_idle_close_by_peer_total 2510
telemt_me_route_drop_no_conn_total 6073
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16817
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2480
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 2382
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 16813
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 110844508 (105.71 MB)
telemt_user_octets_to_client{user="hello"} 3220691480 (3.00 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 8018.5 (2h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24574
telemt_connections_bad_total 76
telemt_handshake_timeouts_total 179
telemt_upstream_connect_attempt_total 2028
telemt_upstream_connect_success_total 2028
telemt_upstream_connect_attempts_per_request{bucket="1"} 2028
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1060
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 1616
telemt_me_reconnect_success_total 1607
telemt_me_reader_eof_total 1671
telemt_me_idle_close_by_peer_total 1671
telemt_me_route_drop_no_conn_total 8036
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22770
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1593
telemt_me_writer_restored_same_endpoint_total 1587
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_user_connections_total{user="hello"} 22766
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 246198720 (234.79 MB)
telemt_user_octets_to_client{user="hello"} 24509294412 (22.83 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 7994.3 (2h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27619
telemt_connections_bad_total 1027
telemt_handshake_timeouts_total 151
telemt_upstream_connect_attempt_total 2285
telemt_upstream_connect_success_total 2227
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 2285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 957
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1263
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 1832
telemt_me_reconnect_success_total 1799
telemt_me_reader_eof_total 1860
telemt_me_idle_close_by_peer_total 1860
telemt_me_route_drop_no_conn_total 8154
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 24419
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 119
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 79
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1826
telemt_me_writer_restored_same_endpoint_total 1791
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 24418
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 638678608 (609.09 MB)
telemt_user_octets_to_client{user="hello"} 8896381444 (8.29 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 7963.6 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15352
telemt_connections_bad_total 1573
telemt_handshake_timeouts_total 190
telemt_upstream_connect_attempt_total 2255
telemt_upstream_connect_success_total 2163
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 2255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 8151
telemt_me_reconnect_success_total 1739
telemt_me_reader_eof_total 1926
telemt_me_idle_close_by_peer_total 1926
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 4435
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13236
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 232
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 167
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 203
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1945
telemt_me_refill_failed_total 200
telemt_me_writer_restored_same_endpoint_total 1725
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 13235
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 61843996 (58.98 MB)
telemt_user_octets_to_client{user="hello"} 3674125140 (3.42 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 7950.7 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38210
telemt_connections_bad_total 532
telemt_handshake_timeouts_total 546
telemt_upstream_connect_attempt_total 1451
telemt_upstream_connect_success_total 1441
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 741
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1034
telemt_me_reconnect_success_total 1026
telemt_me_reader_eof_total 1069
telemt_me_idle_close_by_peer_total 1069
telemt_me_route_drop_no_conn_total 17267
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35684
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 64
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 47
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1041
telemt_me_writer_restored_same_endpoint_total 1019
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 35649
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 1646336904 (1.53 GB)
telemt_user_octets_to_client{user="hello"} 23161463864 (21.57 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 46
```