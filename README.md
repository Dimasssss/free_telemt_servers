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

# Server Metrics 2026-03-13 06:26:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 82410.9 (22h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 311940
telemt_connections_bad_total 3086
telemt_handshake_timeouts_total 6647
telemt_upstream_connect_attempt_total 20794
telemt_upstream_connect_success_total 20696
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 20794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11330
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1619
telemt_me_reconnect_attempts_total 20058
telemt_me_reconnect_success_total 16557
telemt_me_reader_eof_total 17702
telemt_me_idle_close_by_peer_total 17701
telemt_me_route_drop_no_conn_total 97055
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 263531
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 926
telemt_desync_full_logged_total 343
telemt_desync_suppressed_total 583
telemt_desync_frames_bucket_total{bucket="1_2"} 184
telemt_desync_frames_bucket_total{bucket="3_10"} 336
telemt_desync_frames_bucket_total{bucket="gt_10"} 406
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 16844
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 16541
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 263462
telemt_user_connections_current{user="hello"} 278
telemt_user_octets_from_client{user="hello"} 4478226740 (4.17 GB)
telemt_user_octets_to_client{user="hello"} 125841493044 (117.20 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 82303.8 (22h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143006
telemt_connections_bad_total 1421
telemt_handshake_timeouts_total 1062
telemt_upstream_connect_attempt_total 43081
telemt_upstream_connect_success_total 42523
telemt_upstream_connect_fail_total 558
telemt_upstream_connect_attempts_per_request{bucket="1"} 43081
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16845
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 509
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 558
telemt_me_keepalive_timeout_total 626
telemt_me_reconnect_attempts_total 71094
telemt_me_reconnect_success_total 21903
telemt_me_reader_eof_total 24110
telemt_me_idle_close_by_peer_total 24110
telemt_me_route_drop_no_conn_total 53775
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 118842
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 23609
telemt_me_refill_failed_total 1535
telemt_me_writer_restored_same_endpoint_total 21888
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1706
telemt_user_connections_total{user="hello"} 135337
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 1401240640 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 42513596491 (39.59 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 82267.3 (22h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173068
telemt_connections_bad_total 1910
telemt_handshake_timeouts_total 2840
telemt_upstream_connect_attempt_total 22581
telemt_upstream_connect_success_total 22579
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 22581
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12155
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 501
telemt_me_reconnect_attempts_total 19592
telemt_me_reconnect_success_total 18421
telemt_me_reader_eof_total 19748
telemt_me_idle_close_by_peer_total 19748
telemt_me_route_drop_no_conn_total 66818
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161885
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 18620
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 18401
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 161813
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 2954907240 (2.75 GB)
telemt_user_octets_to_client{user="hello"} 72866609224 (67.86 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 82242.9 (22h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 249795
telemt_connections_bad_total 13611
telemt_handshake_timeouts_total 1911
telemt_upstream_connect_attempt_total 35014
telemt_upstream_connect_success_total 25091
telemt_upstream_connect_fail_total 9923
telemt_upstream_connect_attempts_per_request{bucket="1"} 35014
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12300
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9923
telemt_me_keepalive_timeout_total 3347
telemt_me_reconnect_attempts_total 69650
telemt_me_reconnect_success_total 18114
telemt_me_reader_eof_total 20289
telemt_me_idle_close_by_peer_total 20282
telemt_me_route_drop_no_conn_total 90650
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 210315
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 629
telemt_desync_full_logged_total 184
telemt_desync_suppressed_total 445
telemt_desync_frames_bucket_total{bucket="1_2"} 158
telemt_desync_frames_bucket_total{bucket="3_10"} 240
telemt_desync_frames_bucket_total{bucket="gt_10"} 231
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 19955
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 18104
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1841
telemt_user_connections_total{user="hello"} 213055
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 4298907466 (4.00 GB)
telemt_user_octets_to_client{user="hello"} 82454490493 (76.79 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 32414.4 (9h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36995
telemt_connections_bad_total 6737
telemt_handshake_timeouts_total 158
telemt_upstream_connect_attempt_total 11195
telemt_upstream_connect_success_total 11089
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 11195
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6236
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 268
telemt_me_reconnect_attempts_total 10440
telemt_me_reconnect_success_total 9476
telemt_me_reader_eof_total 10099
telemt_me_idle_close_by_peer_total 10099
telemt_me_route_drop_no_conn_total 10185
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29133
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 9591
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 9458
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 29133
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 216344364 (206.32 MB)
telemt_user_octets_to_client{user="hello"} 10008488864 (9.32 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 82199.4 (22h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 421306
telemt_connections_bad_total 8056
telemt_handshake_timeouts_total 3215
telemt_upstream_connect_attempt_total 17541
telemt_upstream_connect_success_total 17445
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 17541
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9291
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 1454
telemt_me_reconnect_attempts_total 16982
telemt_me_reconnect_success_total 13348
telemt_me_reader_eof_total 14337
telemt_me_idle_close_by_peer_total 14334
telemt_me_route_drop_no_conn_total 187156
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 408640
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 361
telemt_desync_full_logged_total 138
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 128
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 13628
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 13341
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 280
telemt_user_connections_total{user="hello"} 396874
telemt_user_connections_current{user="hello"} 427
telemt_user_octets_from_client{user="hello"} 6480677940 (6.04 GB)
telemt_user_octets_to_client{user="hello"} 232808949900 (216.82 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 68
```