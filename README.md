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

# Server Metrics 2026-03-17 08:41:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 50196.8 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 368923
telemt_connections_bad_total 3598
telemt_handshake_timeouts_total 10994
telemt_upstream_connect_attempt_total 10603
telemt_upstream_connect_success_total 10449
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 10603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5523
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_keepalive_timeout_total 81
telemt_me_reconnect_attempts_total 9285
telemt_me_reconnect_success_total 7807
telemt_me_reader_eof_total 8303
telemt_me_idle_close_by_peer_total 8303
telemt_me_route_drop_no_conn_total 116191
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 334215
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2582
telemt_desync_full_logged_total 726
telemt_desync_suppressed_total 1856
telemt_desync_frames_bucket_total{bucket="1_2"} 601
telemt_desync_frames_bucket_total{bucket="3_10"} 1219
telemt_desync_frames_bucket_total{bucket="gt_10"} 762
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7962
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 7786
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 334100
telemt_user_connections_current{user="hello"} 938
telemt_user_octets_from_client{user="hello"} 4711912526 (4.39 GB)
telemt_user_octets_to_client{user="hello"} 136015506418 (126.67 GB)
telemt_user_msgs_from_client{user="hello"} 275
telemt_user_msgs_to_client{user="hello"} 314
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 50448.0 (14h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202396
telemt_connections_bad_total 2371
telemt_handshake_timeouts_total 12275
telemt_upstream_connect_attempt_total 13668
telemt_upstream_connect_success_total 13489
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 13668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7612
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_reconnect_attempts_total 13275
telemt_me_reconnect_success_total 11001
telemt_me_reader_eof_total 11632
telemt_me_idle_close_by_peer_total 11632
telemt_me_route_drop_no_conn_total 73740
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177648
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 464
telemt_desync_full_logged_total 167
telemt_desync_suppressed_total 297
telemt_desync_frames_bucket_total{bucket="1_2"} 139
telemt_desync_frames_bucket_total{bucket="3_10"} 200
telemt_desync_frames_bucket_total{bucket="gt_10"} 125
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 11183
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 10985
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 182
telemt_user_connections_total{user="hello"} 177656
telemt_user_connections_current{user="hello"} 512
telemt_user_octets_from_client{user="hello"} 2146170912 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 71225028112 (66.33 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 50224.1 (13h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124558
telemt_connections_bad_total 7519
telemt_handshake_timeouts_total 6933
telemt_upstream_connect_attempt_total 13289
telemt_upstream_connect_success_total 13219
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 13289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7312
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 11663
telemt_me_reconnect_success_total 10701
telemt_me_reader_eof_total 11448
telemt_me_idle_close_by_peer_total 11448
telemt_me_route_drop_no_conn_total 38704
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 101145
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 265
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 199
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 104
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 10870
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 10690
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 101085
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 6603911372 (6.15 GB)
telemt_user_octets_to_client{user="hello"} 31849211468 (29.66 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 50283.3 (13h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 269743
telemt_connections_bad_total 6175
telemt_handshake_timeouts_total 10576
telemt_upstream_connect_attempt_total 11479
telemt_upstream_connect_success_total 11379
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 11479
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5935
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 9896
telemt_me_reconnect_success_total 8826
telemt_me_reader_eof_total 9391
telemt_me_idle_close_by_peer_total 9391
telemt_me_route_drop_no_conn_total 72779
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 211302
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 444
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 283
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 191
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8990
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 8818
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 164
telemt_user_connections_total{user="hello"} 211290
telemt_user_connections_current{user="hello"} 584
telemt_user_octets_from_client{user="hello"} 2257224302 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 91046139069 (84.79 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 50255.2 (13h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152271
telemt_connections_bad_total 40883
telemt_handshake_timeouts_total 2659
telemt_upstream_connect_attempt_total 15390
telemt_upstream_connect_success_total 15187
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 15390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_reconnect_attempts_total 19683
telemt_me_reconnect_success_total 12576
telemt_me_reader_eof_total 13346
telemt_me_idle_close_by_peer_total 13346
telemt_me_route_drop_no_conn_total 40191
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103924
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 289
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 218
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 101
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 12951
telemt_me_refill_failed_total 220
telemt_me_writer_restored_same_endpoint_total 12568
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 375
telemt_user_connections_total{user="hello"} 103955
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 1682386115 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 48457627226 (45.13 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 50416.5 (14h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 368051
telemt_connections_bad_total 46258
telemt_handshake_timeouts_total 3634
telemt_upstream_connect_attempt_total 10311
telemt_upstream_connect_success_total 10255
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 10311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5004
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5236
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 11642
telemt_me_reconnect_success_total 7766
telemt_me_reader_eof_total 8396
telemt_me_idle_close_by_peer_total 8396
telemt_me_route_drop_no_conn_total 255887
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 375426
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 470
telemt_desync_full_logged_total 191
telemt_desync_suppressed_total 279
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 170
telemt_desync_frames_bucket_total{bucket="gt_10"} 156
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 8000
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 7752
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 297332
telemt_user_connections_current{user="hello"} 802
telemt_user_octets_from_client{user="hello"} 4149421752 (3.86 GB)
telemt_user_octets_to_client{user="hello"} 173684605948 (161.76 GB)
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 38422.8 (10h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3465
telemt_connections_bad_total 207
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 18823
telemt_upstream_connect_success_total 18812
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 18823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 16928
telemt_me_reconnect_success_total 16808
telemt_me_reader_eof_total 18342
telemt_me_idle_close_by_peer_total 18342
telemt_me_route_drop_no_conn_total 674
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3197
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 16962
telemt_me_writer_restored_same_endpoint_total 16808
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 154
telemt_user_connections_total{user="hello"} 3197
telemt_user_connections_current{user="hello"} 57
telemt_user_octets_from_client{user="hello"} 724594584 (691.03 MB)
telemt_user_octets_to_client{user="hello"} 21179451808 (19.72 GB)
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 2
```