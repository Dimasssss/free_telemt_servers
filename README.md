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

# Server Metrics 2026-03-17 09:02:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 51420.6 (14h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 388674
telemt_connections_bad_total 3630
telemt_handshake_timeouts_total 11658
telemt_upstream_connect_attempt_total 13247
telemt_upstream_connect_success_total 12817
telemt_upstream_connect_fail_total 430
telemt_upstream_connect_attempts_per_request{bucket="1"} 13247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5819
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 430
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 9468
telemt_me_reconnect_success_total 7952
telemt_me_reader_eof_total 8453
telemt_me_idle_close_by_peer_total 8452
telemt_me_route_drop_no_conn_total 121923
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 349818
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2699
telemt_desync_full_logged_total 753
telemt_desync_suppressed_total 1946
telemt_desync_frames_bucket_total{bucket="1_2"} 627
telemt_desync_frames_bucket_total{bucket="3_10"} 1256
telemt_desync_frames_bucket_total{bucket="gt_10"} 816
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 8111
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 7930
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 351817
telemt_user_connections_current{user="hello"} 968
telemt_user_octets_from_client{user="hello"} 4878478007 (4.54 GB)
telemt_user_octets_to_client{user="hello"} 140290419047 (130.66 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 51672.6 (14h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211443
telemt_connections_bad_total 2374
telemt_handshake_timeouts_total 12414
telemt_upstream_connect_attempt_total 13900
telemt_upstream_connect_success_total 13715
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 13900
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7706
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_reconnect_attempts_total 15791
telemt_me_reconnect_success_total 11148
telemt_me_reader_eof_total 11854
telemt_me_idle_close_by_peer_total 11854
telemt_me_route_drop_no_conn_total 76659
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 186224
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 503
telemt_desync_full_logged_total 182
telemt_desync_suppressed_total 321
telemt_desync_frames_bucket_total{bucket="1_2"} 150
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 139
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 11405
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 11132
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 186231
telemt_user_connections_current{user="hello"} 536
telemt_user_octets_from_client{user="hello"} 2231995156 (2.08 GB)
telemt_user_octets_to_client{user="hello"} 74867951388 (69.73 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 51448.5 (14h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129841
telemt_connections_bad_total 7567
telemt_handshake_timeouts_total 7901
telemt_upstream_connect_attempt_total 13608
telemt_upstream_connect_success_total 13537
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 13608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5982
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7491
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 11891
telemt_me_reconnect_success_total 10928
telemt_me_reader_eof_total 11696
telemt_me_idle_close_by_peer_total 11696
telemt_me_route_drop_no_conn_total 39856
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105309
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 282
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 208
telemt_desync_frames_bucket_total{bucket="1_2"} 103
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 11099
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 10917
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 105234
telemt_user_connections_current{user="hello"} 289
telemt_user_octets_from_client{user="hello"} 7185225492 (6.69 GB)
telemt_user_octets_to_client{user="hello"} 33641152344 (31.33 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 51507.5 (14h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 282970
telemt_connections_bad_total 6179
telemt_handshake_timeouts_total 10633
telemt_upstream_connect_attempt_total 11807
telemt_upstream_connect_success_total 11700
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 11807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6099
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 10131
telemt_me_reconnect_success_total 9056
telemt_me_reader_eof_total 9638
telemt_me_idle_close_by_peer_total 9638
telemt_me_route_drop_no_conn_total 77620
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 224102
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 467
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 291
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 202
telemt_desync_frames_bucket_total{bucket="gt_10"} 145
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 9228
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9048
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 224061
telemt_user_connections_current{user="hello"} 720
telemt_user_octets_from_client{user="hello"} 2343838274 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 93736479509 (87.30 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 51479.4 (14h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160192
telemt_connections_bad_total 43305
telemt_handshake_timeouts_total 2721
telemt_upstream_connect_attempt_total 15709
telemt_upstream_connect_success_total 15500
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 15709
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8361
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_reconnect_attempts_total 19908
telemt_me_reconnect_success_total 12799
telemt_me_reader_eof_total 13582
telemt_me_idle_close_by_peer_total 13582
telemt_me_route_drop_no_conn_total 41991
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109217
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 328
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 246
telemt_desync_frames_bucket_total{bucket="1_2"} 157
telemt_desync_frames_bucket_total{bucket="3_10"} 114
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 13178
telemt_me_refill_failed_total 220
telemt_me_writer_restored_same_endpoint_total 12791
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 379
telemt_user_connections_total{user="hello"} 109246
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 1735978087 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 50082723002 (46.64 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 51640.7 (14h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 382456
telemt_connections_bad_total 46672
telemt_handshake_timeouts_total 3837
telemt_upstream_connect_attempt_total 10625
telemt_upstream_connect_success_total 10567
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 10625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5378
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 11866
telemt_me_reconnect_success_total 7988
telemt_me_reader_eof_total 8632
telemt_me_idle_close_by_peer_total 8632
telemt_me_route_drop_no_conn_total 261874
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 388362
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 497
telemt_desync_full_logged_total 201
telemt_desync_suppressed_total 296
telemt_desync_frames_bucket_total{bucket="1_2"} 150
telemt_desync_frames_bucket_total{bucket="3_10"} 179
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 8227
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 7974
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 239
telemt_user_connections_total{user="hello"} 310260
telemt_user_connections_current{user="hello"} 899
telemt_user_octets_from_client{user="hello"} 4476441484 (4.17 GB)
telemt_user_octets_to_client{user="hello"} 177378982496 (165.20 GB)
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 39646.9 (11h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4221
telemt_connections_bad_total 220
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 19320
telemt_upstream_connect_success_total 19307
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 19320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8423
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 17375
telemt_me_reconnect_success_total 17248
telemt_me_reader_eof_total 18818
telemt_me_idle_close_by_peer_total 18818
telemt_me_route_drop_no_conn_total 875
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3930
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 17407
telemt_me_writer_restored_same_endpoint_total 17248
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 3930
telemt_user_connections_current{user="hello"} 74
telemt_user_octets_from_client{user="hello"} 731245644 (697.37 MB)
telemt_user_octets_to_client{user="hello"} 22261397200 (20.73 GB)
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 7
```