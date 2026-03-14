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

# Server Metrics 2026-03-14 19:21:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 21932.8 (6h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118310
telemt_connections_bad_total 15772
telemt_handshake_timeouts_total 1117
telemt_upstream_connect_attempt_total 5077
telemt_upstream_connect_success_total 5075
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2588
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 184
telemt_me_reconnect_attempts_total 3958
telemt_me_reconnect_success_total 3925
telemt_me_reader_eof_total 4157
telemt_me_idle_close_by_peer_total 4157
telemt_me_route_drop_no_conn_total 41773
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96278
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 388
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 243
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 146
telemt_desync_frames_bucket_total{bucket="gt_10"} 144
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 3987
telemt_me_writer_restored_same_endpoint_total 3907
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 96206
telemt_user_connections_current{user="hello"} 332
telemt_user_octets_from_client{user="hello"} 1889434768 (1.76 GB)
telemt_user_octets_to_client{user="hello"} 47735079668 (44.46 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 21931.1 (6h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48399
telemt_connections_bad_total 661
telemt_handshake_timeouts_total 901
telemt_upstream_connect_attempt_total 5772
telemt_upstream_connect_success_total 5732
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 5772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3295
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 109
telemt_me_reconnect_attempts_total 7156
telemt_me_reconnect_success_total 4582
telemt_me_reader_eof_total 4873
telemt_me_idle_close_by_peer_total 4873
telemt_me_route_drop_no_conn_total 25478
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45044
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 4725
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 4577
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 45035
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 651432060 (621.25 MB)
telemt_user_octets_to_client{user="hello"} 19083869440 (17.77 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 21935.5 (6h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52346
telemt_connections_bad_total 385
telemt_handshake_timeouts_total 1827
telemt_upstream_connect_attempt_total 7639
telemt_upstream_connect_success_total 7560
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 7639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3952
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 185
telemt_me_reconnect_attempts_total 103954
telemt_me_reconnect_success_total 6092
telemt_me_reader_eof_total 6503
telemt_me_idle_close_by_peer_total 6503
telemt_me_route_drop_no_conn_total 20440
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47293
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 8
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 6357
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 6051
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 265
telemt_user_connections_total{user="hello"} 47357
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 3124496885 (2.91 GB)
telemt_user_octets_to_client{user="hello"} 28599317266 (26.64 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 21940.2 (6h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67017
telemt_connections_bad_total 180
telemt_handshake_timeouts_total 560
telemt_upstream_connect_attempt_total 5382
telemt_upstream_connect_success_total 5348
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 5382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2885
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 106
telemt_me_reconnect_attempts_total 4228
telemt_me_reconnect_success_total 4205
telemt_me_reader_eof_total 4412
telemt_me_idle_close_by_peer_total 4412
telemt_me_route_drop_no_conn_total 29795
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63353
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 543
telemt_desync_full_logged_total 137
telemt_desync_suppressed_total 406
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 223
telemt_desync_frames_bucket_total{bucket="gt_10"} 230
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 4249
telemt_me_writer_restored_same_endpoint_total 4203
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 63229
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 875205532 (834.66 MB)
telemt_user_octets_to_client{user="hello"} 19856236260 (18.49 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 21933.3 (6h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49884
telemt_connections_bad_total 4230
telemt_handshake_timeouts_total 3126
telemt_upstream_connect_attempt_total 5089
telemt_upstream_connect_success_total 5031
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 5089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2745
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 125
telemt_me_reconnect_attempts_total 10409
telemt_me_reconnect_success_total 3881
telemt_me_reader_eof_total 4246
telemt_me_idle_close_by_peer_total 4246
telemt_me_route_drop_no_conn_total 16955
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40151
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 250
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 214
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 4122
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 3877
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 40139
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 623255428 (594.38 MB)
telemt_user_octets_to_client{user="hello"} 12131669660 (11.30 GB)
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 21933.0 (6h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173981
telemt_connections_bad_total 7210
telemt_handshake_timeouts_total 2602
telemt_upstream_connect_attempt_total 4318
telemt_upstream_connect_success_total 4241
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 4318
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2150
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 8092
telemt_me_reconnect_success_total 3092
telemt_me_reader_eof_total 3364
telemt_me_idle_close_by_peer_total 3364
telemt_me_route_drop_no_conn_total 98920
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159077
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 48
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 30
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3281
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 3088
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 155574
telemt_user_connections_current{user="hello"} 421
telemt_user_octets_from_client{user="hello"} 3429709896 (3.19 GB)
telemt_user_octets_to_client{user="hello"} 78672531280 (73.27 GB)
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 53
```