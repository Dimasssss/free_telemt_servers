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

# Server Metrics 2026-03-15 02:24:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 15023.9 (4h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32314
telemt_connections_bad_total 369
telemt_handshake_timeouts_total 281
telemt_upstream_connect_attempt_total 3839
telemt_upstream_connect_success_total 3816
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 3839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1720
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2092
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3062
telemt_me_reconnect_success_total 3048
telemt_me_reader_eof_total 3236
telemt_me_idle_close_by_peer_total 3236
telemt_me_route_drop_no_conn_total 9407
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30696
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 144
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 76
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3060
telemt_me_writer_restored_same_endpoint_total 3017
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 30694
telemt_user_connections_current{user="hello"} 238
telemt_user_octets_from_client{user="hello"} 335733600 (320.18 MB)
telemt_user_octets_to_client{user="hello"} 11724472232 (10.92 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 15030.2 (4h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14077
telemt_connections_bad_total 23
telemt_handshake_timeouts_total 37
telemt_upstream_connect_attempt_total 4194
telemt_upstream_connect_success_total 4194
telemt_upstream_connect_attempts_per_request{bucket="1"} 4194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2349
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 3436
telemt_me_reconnect_success_total 3421
telemt_me_reader_eof_total 3652
telemt_me_idle_close_by_peer_total 3652
telemt_me_route_drop_no_conn_total 6223
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13310
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3445
telemt_me_writer_restored_same_endpoint_total 3405
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 13314
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 539052912 (514.08 MB)
telemt_user_octets_to_client{user="hello"} 3340977572 (3.11 GB)
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 15022.8 (4h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14271
telemt_connections_bad_total 280
telemt_handshake_timeouts_total 251
telemt_upstream_connect_attempt_total 4026
telemt_upstream_connect_success_total 4025
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2232
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 3271
telemt_me_reconnect_success_total 3253
telemt_me_reader_eof_total 3503
telemt_me_idle_close_by_peer_total 3503
telemt_me_route_drop_no_conn_total 5001
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13290
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3277
telemt_me_writer_restored_same_endpoint_total 3249
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 13249
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 8619682132 (8.03 GB)
telemt_user_octets_to_client{user="hello"} 13712728368 (12.77 GB)
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 15022.5 (4h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15776
telemt_connections_bad_total 82
telemt_handshake_timeouts_total 56
telemt_upstream_connect_attempt_total 3619
telemt_upstream_connect_success_total 3618
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1935
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2868
telemt_me_reconnect_success_total 2856
telemt_me_reader_eof_total 3033
telemt_me_idle_close_by_peer_total 3033
telemt_me_route_drop_no_conn_total 6055
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14992
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
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2880
telemt_me_writer_restored_same_endpoint_total 2845
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 14990
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 420279328 (400.81 MB)
telemt_user_octets_to_client{user="hello"} 11937760480 (11.12 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 15022.7 (4h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18105
telemt_connections_bad_total 2994
telemt_handshake_timeouts_total 389
telemt_upstream_connect_attempt_total 4777
telemt_upstream_connect_success_total 4717
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 4777
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2544
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_reconnect_attempts_total 4026
telemt_me_reconnect_success_total 3944
telemt_me_reader_eof_total 4166
telemt_me_idle_close_by_peer_total 4166
telemt_me_route_drop_no_conn_total 5257
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14372
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3959
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 3932
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 14363
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 192337098 (183.43 MB)
telemt_user_octets_to_client{user="hello"} 7285720251 (6.79 GB)
telemt_user_msgs_from_client{user="hello"} 11
telemt_user_msgs_to_client{user="hello"} 7
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 15021.6 (4h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47099
telemt_connections_bad_total 1159
telemt_handshake_timeouts_total 180
telemt_upstream_connect_attempt_total 3377
telemt_upstream_connect_success_total 3356
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 3377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1655
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 2599
telemt_me_reconnect_success_total 2590
telemt_me_reader_eof_total 2721
telemt_me_idle_close_by_peer_total 2721
telemt_me_route_drop_no_conn_total 25716
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45913
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
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2585
telemt_me_writer_restored_same_endpoint_total 2563
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 44482
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 1549746076 (1.44 GB)
telemt_user_octets_to_client{user="hello"} 28044163420 (26.12 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 42
```