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

# Server Metrics 2026-03-12 12:02:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 16138.6 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86185
telemt_connections_bad_total 529
telemt_handshake_timeouts_total 3167
telemt_upstream_connect_attempt_total 3900
telemt_upstream_connect_success_total 3883
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3900
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3074
telemt_me_reconnect_success_total 3056
telemt_me_reader_eof_total 3189
telemt_me_idle_close_by_peer_total 3188
telemt_me_route_drop_no_conn_total 24166
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77617
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 343
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 211
telemt_desync_frames_bucket_total{bucket="1_2"} 70
telemt_desync_frames_bucket_total{bucket="3_10"} 132
telemt_desync_frames_bucket_total{bucket="gt_10"} 141
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3076
telemt_me_writer_restored_same_endpoint_total 3040
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 77584
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 1087121080 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 25793248612 (24.02 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 16031.8 (4h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34247
telemt_connections_bad_total 270
telemt_handshake_timeouts_total 281
telemt_upstream_connect_attempt_total 5111
telemt_upstream_connect_success_total 5002
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 5111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2008
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2984
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 127
telemt_me_reconnect_attempts_total 15945
telemt_me_reconnect_success_total 4186
telemt_me_reader_eof_total 4596
telemt_me_idle_close_by_peer_total 4596
telemt_me_route_drop_no_conn_total 14902
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32568
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 4568
telemt_me_refill_failed_total 367
telemt_me_writer_restored_same_endpoint_total 4171
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 382
telemt_user_connections_total{user="hello"} 32569
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 378650664 (361.11 MB)
telemt_user_octets_to_client{user="hello"} 8575973972 (7.99 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 15995.5 (4h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47036
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 414
telemt_upstream_connect_attempt_total 4369
telemt_upstream_connect_success_total 4369
telemt_upstream_connect_attempts_per_request{bucket="1"} 4369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2220
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 3559
telemt_me_reconnect_success_total 3535
telemt_me_reader_eof_total 3716
telemt_me_idle_close_by_peer_total 3716
telemt_me_route_drop_no_conn_total 16026
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44233
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3551
telemt_me_writer_restored_same_endpoint_total 3515
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 44220
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 1507713196 (1.40 GB)
telemt_user_octets_to_client{user="hello"} 31011109372 (28.88 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 15971.0 (4h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58140
telemt_connections_bad_total 1081
telemt_handshake_timeouts_total 301
telemt_upstream_connect_attempt_total 4486
telemt_upstream_connect_success_total 4377
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 4486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1893
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2473
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 176
telemt_me_reconnect_attempts_total 8711
telemt_me_reconnect_success_total 3548
telemt_me_reader_eof_total 3824
telemt_me_idle_close_by_peer_total 3824
telemt_me_route_drop_no_conn_total 19237
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53114
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 175
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 113
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3755
telemt_me_refill_failed_total 160
telemt_me_writer_restored_same_endpoint_total 3540
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 207
telemt_user_connections_total{user="hello"} 53112
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 1016972104 (969.86 MB)
telemt_user_octets_to_client{user="hello"} 28235192424 (26.30 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 15940.5 (4h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32127
telemt_connections_bad_total 3021
telemt_handshake_timeouts_total 427
telemt_upstream_connect_attempt_total 4506
telemt_upstream_connect_success_total 4307
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 4506
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2758
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 18912
telemt_me_reconnect_success_total 3482
telemt_me_reader_eof_total 3962
telemt_me_idle_close_by_peer_total 3962
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 9676
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27826
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 375
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 266
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 3986
telemt_me_refill_failed_total 483
telemt_me_writer_restored_same_endpoint_total 3465
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 504
telemt_user_connections_total{user="hello"} 27823
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 184555956 (176.01 MB)
telemt_user_octets_to_client{user="hello"} 7178487688 (6.69 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 15927.3 (4h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87746
telemt_connections_bad_total 755
telemt_handshake_timeouts_total 861
telemt_upstream_connect_attempt_total 3194
telemt_upstream_connect_success_total 3178
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1640
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 77
telemt_me_reconnect_attempts_total 2380
telemt_me_reconnect_success_total 2361
telemt_me_reader_eof_total 2482
telemt_me_idle_close_by_peer_total 2482
telemt_me_route_drop_no_conn_total 36681
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83196
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 174
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 112
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2390
telemt_me_writer_restored_same_endpoint_total 2354
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 83163
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 2294618676 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 41813355216 (38.94 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 49
```