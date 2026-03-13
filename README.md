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

# Server Metrics 2026-03-13 12:01:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 102507.3 (28h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 415618
telemt_connections_bad_total 3206
telemt_handshake_timeouts_total 8219
telemt_upstream_connect_attempt_total 25839
telemt_upstream_connect_success_total 25717
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 25839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14072
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2226
telemt_me_reconnect_attempts_total 24114
telemt_me_reconnect_success_total 20590
telemt_me_reader_eof_total 21985
telemt_me_idle_close_by_peer_total 21984
telemt_me_route_drop_no_conn_total 132174
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 360316
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1223
telemt_desync_full_logged_total 435
telemt_desync_suppressed_total 788
telemt_desync_frames_bucket_total{bucket="1_2"} 246
telemt_desync_frames_bucket_total{bucket="3_10"} 451
telemt_desync_frames_bucket_total{bucket="gt_10"} 526
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 20915
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 20574
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 325
telemt_user_connections_total{user="hello"} 359910
telemt_user_connections_current{user="hello"} 365
telemt_user_octets_from_client{user="hello"} 6395570816 (5.96 GB)
telemt_user_octets_to_client{user="hello"} 155028086664 (144.38 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 102399.9 (28h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191367
telemt_connections_bad_total 1653
telemt_handshake_timeouts_total 1460
telemt_upstream_connect_attempt_total 54001
telemt_upstream_connect_success_total 53312
telemt_upstream_connect_fail_total 689
telemt_upstream_connect_attempts_per_request{bucket="1"} 54001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32438
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20340
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 534
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 689
telemt_me_keepalive_timeout_total 1278
telemt_me_reconnect_attempts_total 94186
telemt_me_reconnect_success_total 25923
telemt_me_reader_eof_total 28817
telemt_me_idle_close_by_peer_total 28817
telemt_me_route_drop_no_conn_total 78910
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158336
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 22
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
telemt_me_writer_removed_unexpected_total 28280
telemt_me_refill_failed_total 2129
telemt_me_writer_restored_same_endpoint_total 25906
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2357
telemt_user_connections_total{user="hello"} 180389
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 1843598479 (1.72 GB)
telemt_user_octets_to_client{user="hello"} 58630175225 (54.60 GB)
telemt_user_msgs_from_client{user="hello"} 322437
telemt_user_msgs_to_client{user="hello"} 2292368
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 102364.0 (28h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 232741
telemt_connections_bad_total 2059
telemt_handshake_timeouts_total 6767
telemt_upstream_connect_attempt_total 27857
telemt_upstream_connect_success_total 27853
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 27857
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14937
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2037
telemt_me_reconnect_attempts_total 23896
telemt_me_reconnect_success_total 22685
telemt_me_reader_eof_total 24301
telemt_me_idle_close_by_peer_total 24301
telemt_me_route_drop_no_conn_total 86455
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 215435
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 92
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 22935
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 22665
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 215349
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 9321682408 (8.68 GB)
telemt_user_octets_to_client{user="hello"} 95640986908 (89.07 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 102339.2 (28h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 324706
telemt_connections_bad_total 13736
telemt_handshake_timeouts_total 2337
telemt_upstream_connect_attempt_total 39804
telemt_upstream_connect_success_total 29739
telemt_upstream_connect_fail_total 10065
telemt_upstream_connect_attempts_per_request{bucket="1"} 39804
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15022
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14509
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 199
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10065
telemt_me_keepalive_timeout_total 3960
telemt_me_reconnect_attempts_total 91742
telemt_me_reconnect_success_total 21566
telemt_me_reader_eof_total 24405
telemt_me_idle_close_by_peer_total 24398
telemt_me_route_drop_no_conn_total 117354
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 279918
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 982
telemt_desync_full_logged_total 292
telemt_desync_suppressed_total 690
telemt_desync_frames_bucket_total{bucket="1_2"} 248
telemt_desync_frames_bucket_total{bucket="3_10"} 360
telemt_desync_frames_bucket_total{bucket="gt_10"} 374
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 24027
telemt_me_refill_failed_total 2188
telemt_me_writer_restored_same_endpoint_total 21556
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2461
telemt_user_connections_total{user="hello"} 282830
telemt_user_connections_current{user="hello"} 243
telemt_user_octets_from_client{user="hello"} 5857746622 (5.46 GB)
telemt_user_octets_to_client{user="hello"} 107064829881 (99.71 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 52510.8 (14h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75862
telemt_connections_bad_total 10403
telemt_handshake_timeouts_total 798
telemt_upstream_connect_attempt_total 22992
telemt_upstream_connect_success_total 22813
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 22992
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12196
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10558
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 774
telemt_me_reconnect_attempts_total 25166
telemt_me_reconnect_success_total 15250
telemt_me_reader_eof_total 16370
telemt_me_idle_close_by_peer_total 16370
telemt_me_route_drop_no_conn_total 22332
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57314
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 93
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 15692
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 15232
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 442
telemt_user_connections_total{user="hello"} 62225
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 547439049 (522.08 MB)
telemt_user_octets_to_client{user="hello"} 17219569851 (16.04 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 102295.7 (28h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 581509
telemt_connections_bad_total 17418
telemt_handshake_timeouts_total 13058
telemt_upstream_connect_attempt_total 21754
telemt_upstream_connect_success_total 21641
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 21754
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11472
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 2327
telemt_me_reconnect_attempts_total 21169
telemt_me_reconnect_success_total 16550
telemt_me_reader_eof_total 17764
telemt_me_idle_close_by_peer_total 17761
telemt_me_route_drop_no_conn_total 288305
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 558022
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 458
telemt_desync_full_logged_total 172
telemt_desync_suppressed_total 286
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 175
telemt_desync_frames_bucket_total{bucket="gt_10"} 174
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 16911
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 16543
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 361
telemt_user_connections_total{user="hello"} 531082
telemt_user_connections_current{user="hello"} 446
telemt_user_octets_from_client{user="hello"} 9511306220 (8.86 GB)
telemt_user_octets_to_client{user="hello"} 285192868876 (265.61 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 62
```