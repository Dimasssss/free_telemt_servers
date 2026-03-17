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

# Server Metrics 2026-03-17 05:54:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 40119.2 (11h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 227624
telemt_connections_bad_total 3312
telemt_handshake_timeouts_total 7528
telemt_upstream_connect_attempt_total 8440
telemt_upstream_connect_success_total 8395
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 8440
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4565
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6421
telemt_me_reconnect_success_total 6397
telemt_me_reader_eof_total 6807
telemt_me_idle_close_by_peer_total 6807
telemt_me_route_drop_no_conn_total 70640
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 205379
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1361
telemt_desync_full_logged_total 462
telemt_desync_suppressed_total 899
telemt_desync_frames_bucket_total{bucket="1_2"} 313
telemt_desync_frames_bucket_total{bucket="3_10"} 692
telemt_desync_frames_bucket_total{bucket="gt_10"} 356
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 6461
telemt_me_writer_restored_same_endpoint_total 6376
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 205173
telemt_user_connections_current{user="hello"} 618
telemt_user_octets_from_client{user="hello"} 2783606368 (2.59 GB)
telemt_user_octets_to_client{user="hello"} 91622752976 (85.33 GB)
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 40370.4 (11h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130854
telemt_connections_bad_total 2207
telemt_handshake_timeouts_total 10313
telemt_upstream_connect_attempt_total 11139
telemt_upstream_connect_success_total 10995
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 11139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6329
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_reconnect_attempts_total 10182
telemt_me_reconnect_success_total 9007
telemt_me_reader_eof_total 9525
telemt_me_idle_close_by_peer_total 9525
telemt_me_route_drop_no_conn_total 49799
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113522
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 314
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 200
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 152
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 9126
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 8991
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 113533
telemt_user_connections_current{user="hello"} 257
telemt_user_octets_from_client{user="hello"} 1422450032 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 49099876124 (45.73 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 40146.6 (11h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78543
telemt_connections_bad_total 1108
telemt_handshake_timeouts_total 2618
telemt_upstream_connect_attempt_total 10832
telemt_upstream_connect_success_total 10776
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 10832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5946
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 8807
telemt_me_reconnect_success_total 8759
telemt_me_reader_eof_total 9372
telemt_me_idle_close_by_peer_total 9372
telemt_me_route_drop_no_conn_total 26201
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67394
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 46
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 8866
telemt_me_writer_restored_same_endpoint_total 8748
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 67378
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 6046601992 (5.63 GB)
telemt_user_octets_to_client{user="hello"} 22153307904 (20.63 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 40205.8 (11h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134983
telemt_connections_bad_total 3755
telemt_handshake_timeouts_total 5495
telemt_upstream_connect_attempt_total 9135
telemt_upstream_connect_success_total 9059
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 9135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4776
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_reconnect_attempts_total 7058
telemt_me_reconnect_success_total 7004
telemt_me_reader_eof_total 7451
telemt_me_idle_close_by_peer_total 7451
telemt_me_route_drop_no_conn_total 45034
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121768
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 234
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 163
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 7106
telemt_me_writer_restored_same_endpoint_total 6997
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 121784
telemt_user_connections_current{user="hello"} 300
telemt_user_octets_from_client{user="hello"} 1339054078 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 58734559153 (54.70 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 40177.9 (11h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102644
telemt_connections_bad_total 29534
telemt_handshake_timeouts_total 1973
telemt_upstream_connect_attempt_total 11975
telemt_upstream_connect_success_total 11819
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 11975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6338
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 178
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_reconnect_attempts_total 11970
telemt_me_reconnect_success_total 9708
telemt_me_reader_eof_total 10259
telemt_me_idle_close_by_peer_total 10259
telemt_me_route_drop_no_conn_total 26621
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68393
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 39
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 9905
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 9700
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 197
telemt_user_connections_total{user="hello"} 68490
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 750717871 (715.94 MB)
telemt_user_octets_to_client{user="hello"} 29592512166 (27.56 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 40339.0 (11h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244765
telemt_connections_bad_total 29675
telemt_handshake_timeouts_total 2009
telemt_upstream_connect_attempt_total 8240
telemt_upstream_connect_success_total 8196
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 8240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4278
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 6229
telemt_me_reconnect_success_total 6200
telemt_me_reader_eof_total 6652
telemt_me_idle_close_by_peer_total 6652
telemt_me_route_drop_no_conn_total 205061
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 281881
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 243
telemt_desync_full_logged_total 122
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 6292
telemt_me_writer_restored_same_endpoint_total 6190
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 204133
telemt_user_connections_current{user="hello"} 590
telemt_user_octets_from_client{user="hello"} 3119450560 (2.91 GB)
telemt_user_octets_to_client{user="hello"} 149164221932 (138.92 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 28345.3 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 683
telemt_connections_bad_total 191
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 14015
telemt_upstream_connect_success_total 14015
telemt_upstream_connect_attempts_per_request{bucket="1"} 14015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5959
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 12603
telemt_me_reconnect_success_total 12535
telemt_me_reader_eof_total 13768
telemt_me_idle_close_by_peer_total 13768
telemt_me_route_drop_no_conn_total 67
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 485
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 12650
telemt_me_writer_restored_same_endpoint_total 12535
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 485
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 176608480 (168.43 MB)
telemt_user_octets_to_client{user="hello"} 5127181724 (4.78 GB)
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```