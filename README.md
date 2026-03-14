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

# Server Metrics 2026-03-14 07:48:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 173712.9 (48h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 666397
telemt_connections_bad_total 32382
telemt_handshake_timeouts_total 13138
telemt_upstream_connect_attempt_total 44166
telemt_upstream_connect_success_total 43943
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 44166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23691
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5697
telemt_me_reconnect_attempts_total 39621
telemt_me_reconnect_success_total 34927
telemt_me_reader_eof_total 37350
telemt_me_idle_close_by_peer_total 37349
telemt_me_route_drop_no_conn_total 220259
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 567767
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2173
telemt_desync_full_logged_total 739
telemt_desync_suppressed_total 1434
telemt_desync_frames_bucket_total{bucket="1_2"} 468
telemt_desync_frames_bucket_total{bucket="3_10"} 800
telemt_desync_frames_bucket_total{bucket="gt_10"} 905
telemt_pool_swap_total 160
telemt_me_writer_removed_unexpected_total 35448
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 34907
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 521
telemt_user_connections_total{user="hello"} 567650
telemt_user_connections_current{user="hello"} 386
telemt_user_octets_from_client{user="hello"} 16578613334 (15.44 GB)
telemt_user_octets_to_client{user="hello"} 271791884108 (253.13 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 173605.7 (48h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 335402
telemt_connections_bad_total 2328
telemt_handshake_timeouts_total 2604
telemt_upstream_connect_attempt_total 151261
telemt_upstream_connect_success_total 149976
telemt_upstream_connect_fail_total 1285
telemt_upstream_connect_attempts_per_request{bucket="1"} 151261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 110245
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37305
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2426
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1285
telemt_me_keepalive_timeout_total 4033
telemt_me_reconnect_attempts_total 178631
telemt_me_reconnect_success_total 38037
telemt_me_reader_eof_total 43442
telemt_me_idle_close_by_peer_total 43442
telemt_me_route_drop_no_conn_total 111784
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 214425
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 42791
telemt_me_refill_failed_total 4387
telemt_me_writer_restored_same_endpoint_total 38020
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4754
telemt_user_connections_total{user="hello"} 317531
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 3293346507 (3.07 GB)
telemt_user_octets_to_client{user="hello"} 103525749851 (96.42 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 173569.9 (48h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 392437
telemt_connections_bad_total 3180
telemt_handshake_timeouts_total 35219
telemt_upstream_connect_attempt_total 45817
telemt_upstream_connect_success_total 45808
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 45817
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24794
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3494
telemt_me_reconnect_attempts_total 38422
telemt_me_reconnect_success_total 37135
telemt_me_reader_eof_total 39925
telemt_me_idle_close_by_peer_total 39925
telemt_me_route_drop_no_conn_total 142059
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 340372
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 37584
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 37114
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 449
telemt_user_connections_total{user="hello"} 340143
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 13592717476 (12.66 GB)
telemt_user_octets_to_client{user="hello"} 138338440300 (128.84 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 173545.1 (48h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 494585
telemt_connections_bad_total 16266
telemt_handshake_timeouts_total 4544
telemt_upstream_connect_attempt_total 76300
telemt_upstream_connect_success_total 65703
telemt_upstream_connect_fail_total 10597
telemt_upstream_connect_attempts_per_request{bucket="1"} 76300
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38637
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26714
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 343
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10597
telemt_me_keepalive_timeout_total 5442
telemt_me_reconnect_attempts_total 144101
telemt_me_reconnect_success_total 38038
telemt_me_reader_eof_total 42578
telemt_me_idle_close_by_peer_total 42570
telemt_me_route_drop_no_conn_total 179248
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 421603
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1798
telemt_desync_full_logged_total 538
telemt_desync_suppressed_total 1260
telemt_desync_frames_bucket_total{bucket="1_2"} 428
telemt_desync_frames_bucket_total{bucket="3_10"} 682
telemt_desync_frames_bucket_total{bucket="gt_10"} 688
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 41787
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 38028
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3749
telemt_user_connections_total{user="hello"} 440481
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 9469524923 (8.82 GB)
telemt_user_octets_to_client{user="hello"} 180415172704 (168.02 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 123716.5 (34h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201987
telemt_connections_bad_total 30021
telemt_handshake_timeouts_total 1761
telemt_upstream_connect_attempt_total 43426
telemt_upstream_connect_success_total 43009
telemt_upstream_connect_fail_total 417
telemt_upstream_connect_attempts_per_request{bucket="1"} 43426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21339
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 417
telemt_me_keepalive_timeout_total 2529
telemt_me_reconnect_attempts_total 45398
telemt_me_reconnect_success_total 31964
telemt_me_reader_eof_total 34228
telemt_me_idle_close_by_peer_total 34228
telemt_me_route_drop_no_conn_total 60380
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159773
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 701
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 335
telemt_desync_frames_bucket_total{bucket="gt_10"} 252
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 32681
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 31946
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 717
telemt_user_connections_total{user="hello"} 164530
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 2430281797 (2.26 GB)
telemt_user_octets_to_client{user="hello"} 77938172491 (72.59 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 173501.0 (48h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 995053
telemt_connections_bad_total 36110
telemt_handshake_timeouts_total 26189
telemt_upstream_connect_attempt_total 35951
telemt_upstream_connect_success_total 35762
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 35951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18900
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_keepalive_timeout_total 4723
telemt_me_reconnect_attempts_total 31873
telemt_me_reconnect_success_total 27192
telemt_me_reader_eof_total 29191
telemt_me_idle_close_by_peer_total 29188
telemt_me_route_drop_no_conn_total 468066
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 922013
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 770
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 516
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 253
telemt_desync_frames_bucket_total{bucket="gt_10"} 260
telemt_pool_swap_total 165
telemt_me_writer_removed_unexpected_total 27684
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 27185
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 492
telemt_user_connections_total{user="hello"} 894655
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 15268763084 (14.22 GB)
telemt_user_octets_to_client{user="hello"} 448567517248 (417.76 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 62
```