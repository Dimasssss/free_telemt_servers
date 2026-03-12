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

# Server Metrics 2026-03-12 14:40:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 25640.7 (7h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136126
telemt_connections_bad_total 1420
telemt_handshake_timeouts_total 4546
telemt_upstream_connect_attempt_total 6247
telemt_upstream_connect_success_total 6223
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 6247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3464
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 272
telemt_me_reconnect_attempts_total 4926
telemt_me_reconnect_success_total 4894
telemt_me_reader_eof_total 5148
telemt_me_idle_close_by_peer_total 5147
telemt_me_route_drop_no_conn_total 38617
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 118874
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 565
telemt_desync_full_logged_total 209
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 220
telemt_desync_frames_bucket_total{bucket="gt_10"} 240
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4937
telemt_me_writer_restored_same_endpoint_total 4878
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 118836
telemt_user_connections_current{user="hello"} 383
telemt_user_octets_from_client{user="hello"} 1966591048 (1.83 GB)
telemt_user_octets_to_client{user="hello"} 44263929108 (41.22 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 25533.6 (7h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56591
telemt_connections_bad_total 445
telemt_handshake_timeouts_total 363
telemt_upstream_connect_attempt_total 7798
telemt_upstream_connect_success_total 7624
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 7798
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4450
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_keepalive_timeout_total 170
telemt_me_reconnect_attempts_total 23235
telemt_me_reconnect_success_total 6313
telemt_me_reader_eof_total 6961
telemt_me_idle_close_by_peer_total 6961
telemt_me_route_drop_no_conn_total 25203
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54036
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
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
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 6882
telemt_me_refill_failed_total 528
telemt_me_writer_restored_same_endpoint_total 6298
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 569
telemt_user_connections_total{user="hello"} 54028
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 613622108 (585.20 MB)
telemt_user_octets_to_client{user="hello"} 15708119320 (14.63 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 25497.3 (7h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77802
telemt_connections_bad_total 1428
telemt_handshake_timeouts_total 1465
telemt_upstream_connect_attempt_total 6921
telemt_upstream_connect_success_total 6921
telemt_upstream_connect_attempts_per_request{bucket="1"} 6921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3554
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 5620
telemt_me_reconnect_success_total 5571
telemt_me_reader_eof_total 5896
telemt_me_idle_close_by_peer_total 5896
telemt_me_route_drop_no_conn_total 27367
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71599
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
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 5613
telemt_me_writer_restored_same_endpoint_total 5551
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 71574
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 1928092136 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 40302234176 (37.53 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 25472.8 (7h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98644
telemt_connections_bad_total 2957
telemt_handshake_timeouts_total 728
telemt_upstream_connect_attempt_total 6569
telemt_upstream_connect_success_total 6394
telemt_upstream_connect_fail_total 175
telemt_upstream_connect_attempts_per_request{bucket="1"} 6569
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3498
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 175
telemt_me_keepalive_timeout_total 257
telemt_me_reconnect_attempts_total 20896
telemt_me_reconnect_success_total 5068
telemt_me_reader_eof_total 5695
telemt_me_idle_close_by_peer_total 5695
telemt_me_route_drop_no_conn_total 36282
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 89402
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 287
telemt_desync_full_logged_total 95
telemt_desync_suppressed_total 192
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 5620
telemt_me_refill_failed_total 493
telemt_me_writer_restored_same_endpoint_total 5060
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 552
telemt_user_connections_total{user="hello"} 89285
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 1612409772 (1.50 GB)
telemt_user_octets_to_client{user="hello"} 37514809688 (34.94 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 25442.4 (7h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58403
telemt_connections_bad_total 4942
telemt_handshake_timeouts_total 1048
telemt_upstream_connect_attempt_total 23135
telemt_upstream_connect_success_total 22816
telemt_upstream_connect_fail_total 319
telemt_upstream_connect_attempts_per_request{bucket="1"} 23135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18422
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4366
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 319
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 34175
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 4633
telemt_me_idle_close_by_peer_total 4633
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 12432
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33234
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 8
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
telemt_me_writer_removed_unexpected_total 4658
telemt_me_refill_failed_total 954
telemt_me_writer_restored_same_endpoint_total 3667
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 974
telemt_user_connections_total{user="hello"} 51041
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 422945523 (403.35 MB)
telemt_user_octets_to_client{user="hello"} 12640815278 (11.77 GB)
telemt_user_msgs_from_client{user="hello"} 255311
telemt_user_msgs_to_client{user="hello"} 723946
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 25429.6 (7h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155586
telemt_connections_bad_total 799
telemt_handshake_timeouts_total 1198
telemt_upstream_connect_attempt_total 5211
telemt_upstream_connect_success_total 5184
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 5211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2713
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 3902
telemt_me_reconnect_success_total 3871
telemt_me_reader_eof_total 4082
telemt_me_idle_close_by_peer_total 4082
telemt_me_route_drop_no_conn_total 60923
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 148822
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 231
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 86
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 3917
telemt_me_writer_restored_same_endpoint_total 3864
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 148788
telemt_user_connections_current{user="hello"} 465
telemt_user_octets_from_client{user="hello"} 2944786228 (2.74 GB)
telemt_user_octets_to_client{user="hello"} 63296118436 (58.95 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 81
```