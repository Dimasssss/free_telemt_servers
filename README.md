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

# Server Metrics 2026-03-13 19:24:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 129099.9 (35h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 548160
telemt_connections_bad_total 13059
telemt_handshake_timeouts_total 12433
telemt_upstream_connect_attempt_total 32683
telemt_upstream_connect_success_total 32516
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 32683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17402
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5045
telemt_me_reconnect_attempts_total 30322
telemt_me_reconnect_success_total 25672
telemt_me_reader_eof_total 27420
telemt_me_idle_close_by_peer_total 27419
telemt_me_route_drop_no_conn_total 180552
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 473283
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1517
telemt_desync_full_logged_total 519
telemt_desync_suppressed_total 998
telemt_desync_frames_bucket_total{bucket="1_2"} 332
telemt_desync_frames_bucket_total{bucket="3_10"} 558
telemt_desync_frames_bucket_total{bucket="gt_10"} 627
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 26104
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 25656
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 432
telemt_user_connections_total{user="hello"} 473225
telemt_user_connections_current{user="hello"} 274
telemt_user_octets_from_client{user="hello"} 8753223926 (8.15 GB)
telemt_user_octets_to_client{user="hello"} 225233802612 (209.77 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 128993.0 (35h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 274042
telemt_connections_bad_total 2096
telemt_handshake_timeouts_total 1870
telemt_upstream_connect_attempt_total 125294
telemt_upstream_connect_success_total 124360
telemt_upstream_connect_fail_total 934
telemt_upstream_connect_attempts_per_request{bucket="1"} 125294
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 94275
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27932
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 934
telemt_me_keepalive_timeout_total 3599
telemt_me_reconnect_attempts_total 135149
telemt_me_reconnect_success_total 26243
telemt_me_reader_eof_total 30383
telemt_me_idle_close_by_peer_total 30383
telemt_me_route_drop_no_conn_total 83424
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168199
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 29889
telemt_me_refill_failed_total 3398
telemt_me_writer_restored_same_endpoint_total 26226
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3646
telemt_user_connections_total{user="hello"} 259654
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 2676609062 (2.49 GB)
telemt_user_octets_to_client{user="hello"} 78337662092 (72.96 GB)
telemt_user_msgs_from_client{user="hello"} 1438635
telemt_user_msgs_to_client{user="hello"} 8058544
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 128957.5 (35h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 320781
telemt_connections_bad_total 2631
telemt_handshake_timeouts_total 21611
telemt_upstream_connect_attempt_total 34299
telemt_upstream_connect_success_total 34294
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 34299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18385
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2771
telemt_me_reconnect_attempts_total 29036
telemt_me_reconnect_success_total 27798
telemt_me_reader_eof_total 29828
telemt_me_idle_close_by_peer_total 29828
telemt_me_route_drop_no_conn_total 114697
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 285362
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
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
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 28114
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 27778
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 316
telemt_user_connections_total{user="hello"} 285271
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 11235271416 (10.46 GB)
telemt_user_octets_to_client{user="hello"} 120114157000 (111.87 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 128931.8 (35h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 425759
telemt_connections_bad_total 15174
telemt_handshake_timeouts_total 4072
telemt_upstream_connect_attempt_total 62036
telemt_upstream_connect_success_total 51755
telemt_upstream_connect_fail_total 10281
telemt_upstream_connect_attempts_per_request{bucket="1"} 62036
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18924
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 294
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10281
telemt_me_keepalive_timeout_total 4719
telemt_me_reconnect_attempts_total 116894
telemt_me_reconnect_success_total 26273
telemt_me_reader_eof_total 29869
telemt_me_idle_close_by_peer_total 29862
telemt_me_route_drop_no_conn_total 147171
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 357134
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1434
telemt_desync_full_logged_total 427
telemt_desync_suppressed_total 1007
telemt_desync_frames_bucket_total{bucket="1_2"} 347
telemt_desync_frames_bucket_total{bucket="3_10"} 547
telemt_desync_frames_bucket_total{bucket="gt_10"} 540
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 29439
telemt_me_refill_failed_total 2826
telemt_me_writer_restored_same_endpoint_total 26263
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3166
telemt_user_connections_total{user="hello"} 376013
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 8543332375 (7.96 GB)
telemt_user_octets_to_client{user="hello"} 134872614948 (125.61 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 79103.5 (21h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133534
telemt_connections_bad_total 16317
telemt_handshake_timeouts_total 1422
telemt_upstream_connect_attempt_total 30374
telemt_upstream_connect_success_total 30089
telemt_upstream_connect_fail_total 285
telemt_upstream_connect_attempts_per_request{bucket="1"} 30374
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14447
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 285
telemt_me_keepalive_timeout_total 1227
telemt_me_reconnect_attempts_total 34637
telemt_me_reconnect_success_total 21246
telemt_me_reader_eof_total 22777
telemt_me_idle_close_by_peer_total 22777
telemt_me_route_drop_no_conn_total 41788
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 106546
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 594
telemt_desync_full_logged_total 136
telemt_desync_suppressed_total 458
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 297
telemt_desync_frames_bucket_total{bucket="gt_10"} 214
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 21863
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 21228
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 617
telemt_user_connections_total{user="hello"} 111441
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 1279639549 (1.19 GB)
telemt_user_octets_to_client{user="hello"} 40616355903 (37.83 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 128887.9 (35h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 789639
telemt_connections_bad_total 24786
telemt_handshake_timeouts_total 24857
telemt_upstream_connect_attempt_total 26632
telemt_upstream_connect_success_total 26492
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 26632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14078
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_keepalive_timeout_total 3045
telemt_me_reconnect_attempts_total 24726
telemt_me_reconnect_success_total 20080
telemt_me_reader_eof_total 21550
telemt_me_idle_close_by_peer_total 21547
telemt_me_route_drop_no_conn_total 375751
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 740188
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 691
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 20494
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 20073
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 414
telemt_user_connections_total{user="hello"} 713057
telemt_user_connections_current{user="hello"} 418
telemt_user_octets_from_client{user="hello"} 12371499976 (11.52 GB)
telemt_user_octets_to_client{user="hello"} 351891814096 (327.72 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 42
```