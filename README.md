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

# Server Metrics 2026-03-14 19:32:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 22546.3 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120819
telemt_connections_bad_total 15847
telemt_handshake_timeouts_total 1139
telemt_upstream_connect_attempt_total 5144
telemt_upstream_connect_success_total 5142
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2620
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 184
telemt_me_reconnect_attempts_total 4011
telemt_me_reconnect_success_total 3977
telemt_me_reader_eof_total 4211
telemt_me_idle_close_by_peer_total 4211
telemt_me_route_drop_no_conn_total 42715
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98537
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 408
telemt_desync_full_logged_total 150
telemt_desync_suppressed_total 258
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 154
telemt_desync_frames_bucket_total{bucket="gt_10"} 152
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4041
telemt_me_writer_restored_same_endpoint_total 3959
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 98465
telemt_user_connections_current{user="hello"} 372
telemt_user_octets_from_client{user="hello"} 1940659668 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 49263069152 (45.88 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 22544.2 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49143
telemt_connections_bad_total 668
telemt_handshake_timeouts_total 906
telemt_upstream_connect_attempt_total 5866
telemt_upstream_connect_success_total 5826
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 5866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3354
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 7239
telemt_me_reconnect_success_total 4664
telemt_me_reader_eof_total 4957
telemt_me_idle_close_by_peer_total 4957
telemt_me_route_drop_no_conn_total 25961
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45754
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
telemt_me_writer_removed_unexpected_total 4809
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 4659
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 45745
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 660100572 (629.52 MB)
telemt_user_octets_to_client{user="hello"} 19408890624 (18.08 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 22548.8 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53873
telemt_connections_bad_total 385
telemt_handshake_timeouts_total 1830
telemt_upstream_connect_attempt_total 7743
telemt_upstream_connect_success_total 7664
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 7743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3642
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4017
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 104048
telemt_me_reconnect_success_total 6186
telemt_me_reader_eof_total 6599
telemt_me_idle_close_by_peer_total 6599
telemt_me_route_drop_no_conn_total 20897
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48735
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
telemt_me_writer_removed_unexpected_total 6453
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 6145
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 48799
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 3148525221 (2.93 GB)
telemt_user_octets_to_client{user="hello"} 33842814570 (31.52 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 22553.6 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68869
telemt_connections_bad_total 180
telemt_handshake_timeouts_total 566
telemt_upstream_connect_attempt_total 5495
telemt_upstream_connect_success_total 5461
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 5495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2953
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 4323
telemt_me_reconnect_success_total 4299
telemt_me_reader_eof_total 4507
telemt_me_idle_close_by_peer_total 4507
telemt_me_route_drop_no_conn_total 30443
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 65133
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 561
telemt_desync_full_logged_total 142
telemt_desync_suppressed_total 419
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 229
telemt_desync_frames_bucket_total{bucket="gt_10"} 237
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 4344
telemt_me_writer_restored_same_endpoint_total 4297
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 65009
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 911984188 (869.74 MB)
telemt_user_octets_to_client{user="hello"} 20389244124 (18.99 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 22546.6 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51079
telemt_connections_bad_total 4354
telemt_handshake_timeouts_total 3212
telemt_upstream_connect_attempt_total 5199
telemt_upstream_connect_success_total 5139
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 5199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2803
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 128
telemt_me_reconnect_attempts_total 10506
telemt_me_reconnect_success_total 3976
telemt_me_reader_eof_total 4342
telemt_me_idle_close_by_peer_total 4342
telemt_me_route_drop_no_conn_total 17372
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41102
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 251
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 214
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 4218
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 3972
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 242
telemt_user_connections_total{user="hello"} 41090
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 636124208 (606.66 MB)
telemt_user_octets_to_client{user="hello"} 13843911936 (12.89 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 22546.7 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 178045
telemt_connections_bad_total 7212
telemt_handshake_timeouts_total 2613
telemt_upstream_connect_attempt_total 4393
telemt_upstream_connect_success_total 4316
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 4393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2193
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 8156
telemt_me_reconnect_success_total 3155
telemt_me_reader_eof_total 3428
telemt_me_idle_close_by_peer_total 3428
telemt_me_route_drop_no_conn_total 101018
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162992
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
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3345
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 3151
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 159489
telemt_user_connections_current{user="hello"} 451
telemt_user_octets_from_client{user="hello"} 3469678644 (3.23 GB)
telemt_user_octets_to_client{user="hello"} 79770277628 (74.29 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 58
```