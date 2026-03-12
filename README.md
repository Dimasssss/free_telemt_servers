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

# Server Metrics 2026-03-12 17:55:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 37321.2 (10h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 193033
telemt_connections_bad_total 2414
telemt_handshake_timeouts_total 4940
telemt_upstream_connect_attempt_total 9497
telemt_upstream_connect_success_total 9454
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 9497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4211
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5218
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1372
telemt_me_reconnect_attempts_total 10978
telemt_me_reconnect_success_total 7523
telemt_me_reader_eof_total 7972
telemt_me_idle_close_by_peer_total 7971
telemt_me_route_drop_no_conn_total 57323
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163311
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 630
telemt_desync_full_logged_total 237
telemt_desync_suppressed_total 393
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 240
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 7716
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 7507
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 193
telemt_user_connections_total{user="hello"} 163271
telemt_user_connections_current{user="hello"} 269
telemt_user_octets_from_client{user="hello"} 2906923668 (2.71 GB)
telemt_user_octets_to_client{user="hello"} 69836060676 (65.04 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 37213.9 (10h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82246
telemt_connections_bad_total 469
telemt_handshake_timeouts_total 661
telemt_upstream_connect_attempt_total 13719
telemt_upstream_connect_success_total 13472
telemt_upstream_connect_fail_total 247
telemt_upstream_connect_attempts_per_request{bucket="1"} 13719
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6688
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 247
telemt_me_keepalive_timeout_total 323
telemt_me_reconnect_attempts_total 38795
telemt_me_reconnect_success_total 8998
telemt_me_reader_eof_total 10102
telemt_me_idle_close_by_peer_total 10102
telemt_me_route_drop_no_conn_total 35093
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75605
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 9
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
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 10002
telemt_me_refill_failed_total 930
telemt_me_writer_restored_same_endpoint_total 8983
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1004
telemt_user_connections_total{user="hello"} 78164
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 858897935 (819.11 MB)
telemt_user_octets_to_client{user="hello"} 21431296715 (19.96 GB)
telemt_user_msgs_from_client{user="hello"} 42775
telemt_user_msgs_to_client{user="hello"} 249117
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 37177.5 (10h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109520
telemt_connections_bad_total 1507
telemt_handshake_timeouts_total 2095
telemt_upstream_connect_attempt_total 10241
telemt_upstream_connect_success_total 10241
telemt_upstream_connect_attempts_per_request{bucket="1"} 10241
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5281
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 230
telemt_me_reconnect_attempts_total 8363
telemt_me_reconnect_success_total 8289
telemt_me_reader_eof_total 8780
telemt_me_idle_close_by_peer_total 8780
telemt_me_route_drop_no_conn_total 40927
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 101415
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 8367
telemt_me_writer_restored_same_endpoint_total 8269
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 101387
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 2359756004 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 52790587340 (49.17 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 37153.4 (10h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149523
telemt_connections_bad_total 13088
telemt_handshake_timeouts_total 1111
telemt_upstream_connect_attempt_total 8410
telemt_upstream_connect_success_total 8145
telemt_upstream_connect_fail_total 265
telemt_upstream_connect_attempts_per_request{bucket="1"} 8410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4309
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 265
telemt_me_keepalive_timeout_total 372
telemt_me_reconnect_attempts_total 35478
telemt_me_reconnect_success_total 6234
telemt_me_reader_eof_total 7288
telemt_me_idle_close_by_peer_total 7288
telemt_me_route_drop_no_conn_total 54330
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 127965
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 432
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 307
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 163
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 7217
telemt_me_refill_failed_total 912
telemt_me_writer_restored_same_endpoint_total 6226
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 983
telemt_user_connections_total{user="hello"} 127847
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 2262730988 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 52670267784 (49.05 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 37122.6 (10h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93469
telemt_connections_bad_total 9652
telemt_handshake_timeouts_total 1165
telemt_upstream_connect_attempt_total 49892
telemt_upstream_connect_success_total 49444
telemt_upstream_connect_fail_total 448
telemt_upstream_connect_attempts_per_request{bucket="1"} 49892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7103
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 448
telemt_me_keepalive_timeout_total 138
telemt_me_reconnect_attempts_total 51915
telemt_me_reconnect_success_total 3734
telemt_me_reader_eof_total 5237
telemt_me_idle_close_by_peer_total 5237
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 13561
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35811
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 5265
telemt_me_refill_failed_total 1508
telemt_me_writer_restored_same_endpoint_total 3717
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1531
telemt_user_connections_total{user="hello"} 79614
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 718814113 (685.51 MB)
telemt_user_octets_to_client{user="hello"} 23177108108 (21.59 GB)
telemt_user_msgs_from_client{user="hello"} 676480
telemt_user_msgs_to_client{user="hello"} 2551875
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 37110.0 (10h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236802
telemt_connections_bad_total 1263
telemt_handshake_timeouts_total 2017
telemt_upstream_connect_attempt_total 7954
telemt_upstream_connect_success_total 7916
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 7954
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4216
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 455
telemt_me_reconnect_attempts_total 9611
telemt_me_reconnect_success_total 6009
telemt_me_reader_eof_total 6406
telemt_me_idle_close_by_peer_total 6405
telemt_me_route_drop_no_conn_total 108601
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 235936
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 255
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 6199
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 6002
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 225869
telemt_user_connections_current{user="hello"} 408
telemt_user_octets_from_client{user="hello"} 4025326492 (3.75 GB)
telemt_user_octets_to_client{user="hello"} 105116243708 (97.90 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 62
```