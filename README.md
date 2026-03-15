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

# Server Metrics 2026-03-15 15:39:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 62685.3 (17h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 285536
telemt_connections_bad_total 2781
telemt_handshake_timeouts_total 8801
telemt_upstream_connect_attempt_total 15676
telemt_upstream_connect_success_total 15593
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 15676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8688
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 15844
telemt_me_reconnect_success_total 12461
telemt_me_reader_eof_total 13273
telemt_me_idle_close_by_peer_total 13273
telemt_me_route_drop_no_conn_total 447580
telemt_me_route_drop_channel_closed_total 72
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 323706
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1751
telemt_desync_full_logged_total 699
telemt_desync_suppressed_total 1052
telemt_desync_frames_bucket_total{bucket="1_2"} 314
telemt_desync_frames_bucket_total{bucket="3_10"} 691
telemt_desync_frames_bucket_total{bucket="gt_10"} 746
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 12697
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 12427
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 236
telemt_user_connections_total{user="hello"} 262808
telemt_user_connections_current{user="hello"} 325
telemt_user_octets_from_client{user="hello"} 5690670632 (5.30 GB)
telemt_user_octets_to_client{user="hello"} 221361504076 (206.16 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 62692.7 (17h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108607
telemt_connections_bad_total 2807
telemt_handshake_timeouts_total 10375
telemt_upstream_connect_attempt_total 17276
telemt_upstream_connect_success_total 17276
telemt_upstream_connect_attempts_per_request{bucket="1"} 17276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9676
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 163
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 16460
telemt_me_reconnect_success_total 14102
telemt_me_reader_eof_total 15074
telemt_me_idle_close_by_peer_total 15074
telemt_me_route_drop_no_conn_total 44935
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92154
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 14341
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 14086
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 239
telemt_user_connections_total{user="hello"} 92140
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 1841553040 (1.72 GB)
telemt_user_octets_to_client{user="hello"} 47062482836 (43.83 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 62685.4 (17h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116360
telemt_connections_bad_total 1660
telemt_handshake_timeouts_total 2909
telemt_upstream_connect_attempt_total 18473
telemt_upstream_connect_success_total 18465
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 18473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10425
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 22626
telemt_me_reconnect_success_total 15277
telemt_me_reader_eof_total 16413
telemt_me_idle_close_by_peer_total 16413
telemt_me_route_drop_no_conn_total 44891
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100897
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 56
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 15647
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 15269
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 100796
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 10355010388 (9.64 GB)
telemt_user_octets_to_client{user="hello"} 58603780616 (54.58 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 62684.9 (17h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 154339
telemt_connections_bad_total 872
telemt_handshake_timeouts_total 959
telemt_upstream_connect_attempt_total 15095
telemt_upstream_connect_success_total 15089
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 15095
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7769
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 12027
telemt_me_reconnect_success_total 11954
telemt_me_reader_eof_total 12715
telemt_me_idle_close_by_peer_total 12715
telemt_me_route_drop_no_conn_total 60182
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 141634
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 501
telemt_desync_full_logged_total 166
telemt_desync_suppressed_total 335
telemt_desync_frames_bucket_total{bucket="1_2"} 107
telemt_desync_frames_bucket_total{bucket="3_10"} 228
telemt_desync_frames_bucket_total{bucket="gt_10"} 166
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 12092
telemt_me_writer_restored_same_endpoint_total 11943
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 141547
telemt_user_connections_current{user="hello"} 241
telemt_user_octets_from_client{user="hello"} 2733793416 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 67359038896 (62.73 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 37756.4 (10h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92032
telemt_connections_bad_total 22197
telemt_handshake_timeouts_total 2145
telemt_upstream_connect_attempt_total 11657
telemt_upstream_connect_success_total 11588
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 11657
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6290
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 103962
telemt_me_reconnect_success_total 9528
telemt_me_reader_eof_total 9973
telemt_me_idle_close_by_peer_total 9973
telemt_me_route_drop_no_conn_total 31343
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 65562
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 158
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 122
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 9560
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 9424
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 65698
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 912670701 (870.39 MB)
telemt_user_octets_to_client{user="hello"} 27728262435 (25.82 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 62684.9 (17h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 389466
telemt_connections_bad_total 49944
telemt_handshake_timeouts_total 3325
telemt_upstream_connect_attempt_total 13450
telemt_upstream_connect_success_total 13371
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 13450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6743
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 11505
telemt_me_reconnect_success_total 10209
telemt_me_reader_eof_total 10866
telemt_me_idle_close_by_peer_total 10866
telemt_me_route_drop_no_conn_total 216183
telemt_me_route_drop_channel_closed_total 48
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 341447
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 307
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 226
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 10351
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 10182
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 322224
telemt_user_connections_current{user="hello"} 568
telemt_user_octets_from_client{user="hello"} 8224532160 (7.66 GB)
telemt_user_octets_to_client{user="hello"} 169594460800 (157.95 GB)
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 61
```