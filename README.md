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

# Server Metrics 2026-03-15 02:45:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 16245.4 (4h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35551
telemt_connections_bad_total 370
telemt_handshake_timeouts_total 283
telemt_upstream_connect_attempt_total 4128
telemt_upstream_connect_success_total 4103
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 4127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2256
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3294
telemt_me_reconnect_success_total 3280
telemt_me_reader_eof_total 3481
telemt_me_idle_close_by_peer_total 3481
telemt_me_route_drop_no_conn_total 10552
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33766
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 164
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 89
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3293
telemt_me_writer_restored_same_endpoint_total 3249
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 33764
telemt_user_connections_current{user="hello"} 244
telemt_user_octets_from_client{user="hello"} 370302072 (353.15 MB)
telemt_user_octets_to_client{user="hello"} 12351322116 (11.50 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 16251.9 (4h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14604
telemt_connections_bad_total 26
telemt_handshake_timeouts_total 37
telemt_upstream_connect_attempt_total 4533
telemt_upstream_connect_success_total 4533
telemt_upstream_connect_attempts_per_request{bucket="1"} 4533
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2524
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 3710
telemt_me_reconnect_success_total 3694
telemt_me_reader_eof_total 3941
telemt_me_idle_close_by_peer_total 3941
telemt_me_route_drop_no_conn_total 6677
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13816
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3719
telemt_me_writer_restored_same_endpoint_total 3678
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 13820
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 571385680 (544.92 MB)
telemt_user_octets_to_client{user="hello"} 3487236708 (3.25 GB)
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 16244.4 (4h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15171
telemt_connections_bad_total 285
telemt_handshake_timeouts_total 262
telemt_upstream_connect_attempt_total 4360
telemt_upstream_connect_success_total 4359
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4360
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2436
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 3546
telemt_me_reconnect_success_total 3527
telemt_me_reader_eof_total 3793
telemt_me_idle_close_by_peer_total 3793
telemt_me_route_drop_no_conn_total 5230
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14147
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3553
telemt_me_writer_restored_same_endpoint_total 3523
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 14105
telemt_user_connections_current{user="hello"} 56
telemt_user_octets_from_client{user="hello"} 8639026352 (8.05 GB)
telemt_user_octets_to_client{user="hello"} 13776839860 (12.83 GB)
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 16244.1 (4h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17098
telemt_connections_bad_total 88
telemt_handshake_timeouts_total 58
telemt_upstream_connect_attempt_total 3920
telemt_upstream_connect_success_total 3919
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2104
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 3109
telemt_me_reconnect_success_total 3097
telemt_me_reader_eof_total 3291
telemt_me_idle_close_by_peer_total 3291
telemt_me_route_drop_no_conn_total 6571
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16224
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 55
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3124
telemt_me_writer_restored_same_endpoint_total 3086
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 16222
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 424418532 (404.76 MB)
telemt_user_octets_to_client{user="hello"} 12051836496 (11.22 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 16244.3 (4h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19089
telemt_connections_bad_total 3216
telemt_handshake_timeouts_total 394
telemt_upstream_connect_attempt_total 5104
telemt_upstream_connect_success_total 5039
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 5104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2725
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_reconnect_attempts_total 4297
telemt_me_reconnect_success_total 4214
telemt_me_reader_eof_total 4453
telemt_me_idle_close_by_peer_total 4453
telemt_me_route_drop_no_conn_total 5532
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15114
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 4232
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 4202
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 15105
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 195492326 (186.44 MB)
telemt_user_octets_to_client{user="hello"} 7397070771 (6.89 GB)
telemt_user_msgs_from_client{user="hello"} 11
telemt_user_msgs_to_client{user="hello"} 7
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 16243.3 (4h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50310
telemt_connections_bad_total 1202
telemt_handshake_timeouts_total 181
telemt_upstream_connect_attempt_total 3620
telemt_upstream_connect_success_total 3599
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 3620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1820
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1778
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 2785
telemt_me_reconnect_success_total 2775
telemt_me_reader_eof_total 2918
telemt_me_idle_close_by_peer_total 2918
telemt_me_route_drop_no_conn_total 27218
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48961
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2772
telemt_me_writer_restored_same_endpoint_total 2748
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 47530
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 1660187532 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 28932555752 (26.95 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 35
```