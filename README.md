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

# Server Metrics 2026-03-14 19:57:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 24079.2 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127034
telemt_connections_bad_total 15958
telemt_handshake_timeouts_total 1202
telemt_upstream_connect_attempt_total 5454
telemt_upstream_connect_success_total 5452
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5454
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2784
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4249
telemt_me_reconnect_success_total 4214
telemt_me_reader_eof_total 4467
telemt_me_idle_close_by_peer_total 4467
telemt_me_route_drop_no_conn_total 45298
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 104262
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 445
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 284
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 162
telemt_desync_frames_bucket_total{bucket="gt_10"} 174
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4284
telemt_me_writer_restored_same_endpoint_total 4196
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 104183
telemt_user_connections_current{user="hello"} 328
telemt_user_octets_from_client{user="hello"} 2177093596 (2.03 GB)
telemt_user_octets_to_client{user="hello"} 53875100200 (50.18 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 24077.6 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51543
telemt_connections_bad_total 683
telemt_handshake_timeouts_total 943
telemt_upstream_connect_attempt_total 6240
telemt_upstream_connect_success_total 6199
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 6240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 7537
telemt_me_reconnect_success_total 4962
telemt_me_reader_eof_total 5276
telemt_me_idle_close_by_peer_total 5276
telemt_me_route_drop_no_conn_total 27312
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47992
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 5110
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 4957
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 47981
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 1283903884 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 20001031732 (18.63 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 24081.8 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57316
telemt_connections_bad_total 386
telemt_handshake_timeouts_total 1866
telemt_upstream_connect_attempt_total 8151
telemt_upstream_connect_success_total 8068
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 8151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4254
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 224
telemt_me_reconnect_attempts_total 104374
telemt_me_reconnect_success_total 6511
telemt_me_reader_eof_total 6949
telemt_me_idle_close_by_peer_total 6949
telemt_me_route_drop_no_conn_total 22054
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52006
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 9
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
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 6781
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 6469
telemt_me_writer_restored_fallback_total 42
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 52073
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 3335585017 (3.11 GB)
telemt_user_octets_to_client{user="hello"} 39458291002 (36.75 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 24086.6 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73362
telemt_connections_bad_total 203
telemt_handshake_timeouts_total 568
telemt_upstream_connect_attempt_total 5992
telemt_upstream_connect_success_total 5956
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 5992
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2794
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3136
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 164
telemt_me_reconnect_attempts_total 4578
telemt_me_reconnect_success_total 4553
telemt_me_reader_eof_total 4783
telemt_me_idle_close_by_peer_total 4783
telemt_me_route_drop_no_conn_total 31917
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69343
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 572
telemt_desync_full_logged_total 144
telemt_desync_suppressed_total 428
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 236
telemt_desync_frames_bucket_total{bucket="gt_10"} 240
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4605
telemt_me_writer_restored_same_endpoint_total 4551
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 69391
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 1001795588 (955.39 MB)
telemt_user_octets_to_client{user="hello"} 22194689970 (20.67 GB)
telemt_user_msgs_from_client{user="hello"} 473
telemt_user_msgs_to_client{user="hello"} 2783
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 24079.7 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53826
telemt_connections_bad_total 4668
telemt_handshake_timeouts_total 3235
telemt_upstream_connect_attempt_total 5600
telemt_upstream_connect_success_total 5539
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 5600
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2486
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 134
telemt_me_reconnect_attempts_total 10830
telemt_me_reconnect_success_total 4297
telemt_me_reader_eof_total 4686
telemt_me_idle_close_by_peer_total 4686
telemt_me_route_drop_no_conn_total 18175
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43389
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 252
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 214
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 4543
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 4293
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 246
telemt_user_connections_total{user="hello"} 43376
telemt_user_connections_current{user="hello"} 68
telemt_user_octets_from_client{user="hello"} 1333947068 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 21900444476 (20.40 GB)
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 24079.6 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187288
telemt_connections_bad_total 7233
telemt_handshake_timeouts_total 2622
telemt_upstream_connect_attempt_total 4702
telemt_upstream_connect_success_total 4619
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 4702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2265
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2350
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 176
telemt_me_reconnect_attempts_total 8386
telemt_me_reconnect_success_total 3383
telemt_me_reader_eof_total 3672
telemt_me_idle_close_by_peer_total 3672
telemt_me_route_drop_no_conn_total 105639
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171928
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 55
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 35
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3576
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 3379
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 193
telemt_user_connections_total{user="hello"} 168417
telemt_user_connections_current{user="hello"} 407
telemt_user_octets_from_client{user="hello"} 3581071816 (3.34 GB)
telemt_user_octets_to_client{user="hello"} 83421943248 (77.69 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 47
```