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

# Server Metrics 2026-03-12 16:48:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 33324.0 (9h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175143
telemt_connections_bad_total 2041
telemt_handshake_timeouts_total 4870
telemt_upstream_connect_attempt_total 8223
telemt_upstream_connect_success_total 8193
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 8223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4565
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 331
telemt_me_reconnect_attempts_total 7631
telemt_me_reconnect_success_total 6497
telemt_me_reader_eof_total 6856
telemt_me_idle_close_by_peer_total 6855
telemt_me_route_drop_no_conn_total 51172
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149576
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 624
telemt_desync_full_logged_total 233
telemt_desync_suppressed_total 391
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 237
telemt_desync_frames_bucket_total{bucket="gt_10"} 267
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 6595
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 6481
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 149535
telemt_user_connections_current{user="hello"} 341
telemt_user_octets_from_client{user="hello"} 2540920172 (2.37 GB)
telemt_user_octets_to_client{user="hello"} 59668727724 (55.57 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 33216.6 (9h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74022
telemt_connections_bad_total 466
telemt_handshake_timeouts_total 623
telemt_upstream_connect_attempt_total 10543
telemt_upstream_connect_success_total 10328
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 10543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6156
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_timeout_total 272
telemt_me_reconnect_attempts_total 31795
telemt_me_reconnect_success_total 8659
telemt_me_reader_eof_total 9550
telemt_me_idle_close_by_peer_total 9550
telemt_me_route_drop_no_conn_total 32241
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 70290
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
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
telemt_me_writer_removed_unexpected_total 9448
telemt_me_refill_failed_total 722
telemt_me_writer_restored_same_endpoint_total 8644
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 789
telemt_user_connections_total{user="hello"} 70275
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 785196048 (748.82 MB)
telemt_user_octets_to_client{user="hello"} 19493846876 (18.16 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 33180.0 (9h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99575
telemt_connections_bad_total 1492
telemt_handshake_timeouts_total 2044
telemt_upstream_connect_attempt_total 9231
telemt_upstream_connect_success_total 9231
telemt_upstream_connect_attempts_per_request{bucket="1"} 9231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4756
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 173
telemt_me_reconnect_attempts_total 7572
telemt_me_reconnect_success_total 7505
telemt_me_reader_eof_total 7942
telemt_me_idle_close_by_peer_total 7942
telemt_me_route_drop_no_conn_total 36790
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91940
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 7574
telemt_me_writer_restored_same_endpoint_total 7485
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 91914
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 2255879124 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 47078636108 (43.85 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 33156.0 (9h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136724
telemt_connections_bad_total 13065
telemt_handshake_timeouts_total 1009
telemt_upstream_connect_attempt_total 7298
telemt_upstream_connect_success_total 7075
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 7298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3770
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_keepalive_timeout_total 325
telemt_me_reconnect_attempts_total 32105
telemt_me_reconnect_success_total 5395
telemt_me_reader_eof_total 6362
telemt_me_idle_close_by_peer_total 6362
telemt_me_route_drop_no_conn_total 48805
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115661
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 398
telemt_desync_full_logged_total 119
telemt_desync_suppressed_total 279
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 149
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 6291
telemt_me_refill_failed_total 833
telemt_me_writer_restored_same_endpoint_total 5387
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 896
telemt_user_connections_total{user="hello"} 115541
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 2143676708 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 49991212692 (46.56 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 33125.2 (9h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80726
telemt_connections_bad_total 8766
telemt_handshake_timeouts_total 1127
telemt_upstream_connect_attempt_total 40336
telemt_upstream_connect_success_total 39931
telemt_upstream_connect_fail_total 405
telemt_upstream_connect_attempts_per_request{bucket="1"} 40336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5928
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 405
telemt_me_keepalive_timeout_total 137
telemt_me_reconnect_attempts_total 45173
telemt_me_reconnect_success_total 3690
telemt_me_reader_eof_total 4981
telemt_me_idle_close_by_peer_total 4981
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 12994
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34443
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 11
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
telemt_me_writer_removed_unexpected_total 5009
telemt_me_refill_failed_total 1299
telemt_me_writer_restored_same_endpoint_total 3673
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1319
telemt_user_connections_total{user="hello"} 69005
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 613851339 (585.41 MB)
telemt_user_octets_to_client{user="hello"} 20519443930 (19.11 GB)
telemt_user_msgs_from_client{user="hello"} 546676
telemt_user_msgs_to_client{user="hello"} 2079412
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 33112.7 (9h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209429
telemt_connections_bad_total 966
telemt_handshake_timeouts_total 1700
telemt_upstream_connect_attempt_total 7064
telemt_upstream_connect_success_total 7029
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 7064
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3730
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 401
telemt_me_reconnect_attempts_total 6418
telemt_me_reconnect_success_total 5350
telemt_me_reader_eof_total 5645
telemt_me_idle_close_by_peer_total 5644
telemt_me_route_drop_no_conn_total 88352
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 205060
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 253
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 153
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5454
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 5343
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 199938
telemt_user_connections_current{user="hello"} 493
telemt_user_octets_from_client{user="hello"} 3719178580 (3.46 GB)
telemt_user_octets_to_client{user="hello"} 89976460312 (83.80 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 58
```