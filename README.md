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

# Server Metrics 2026-03-14 02:07:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 153239.3 (42h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 600697
telemt_connections_bad_total 22318
telemt_handshake_timeouts_total 12898
telemt_upstream_connect_attempt_total 39118
telemt_upstream_connect_success_total 38925
telemt_upstream_connect_fail_total 193
telemt_upstream_connect_attempts_per_request{bucket="1"} 39118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20959
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 193
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5504
telemt_me_reconnect_attempts_total 35553
telemt_me_reconnect_success_total 30877
telemt_me_reader_eof_total 32990
telemt_me_idle_close_by_peer_total 32989
telemt_me_route_drop_no_conn_total 197075
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 514394
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1660
telemt_desync_full_logged_total 571
telemt_desync_suppressed_total 1089
telemt_desync_frames_bucket_total{bucket="1_2"} 355
telemt_desync_frames_bucket_total{bucket="3_10"} 626
telemt_desync_frames_bucket_total{bucket="gt_10"} 679
telemt_pool_swap_total 139
telemt_me_writer_removed_unexpected_total 31364
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 30861
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 487
telemt_user_connections_total{user="hello"} 514286
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 15597112178 (14.53 GB)
telemt_user_octets_to_client{user="hello"} 253030363524 (235.65 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 153132.3 (42h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 307738
telemt_connections_bad_total 2247
telemt_handshake_timeouts_total 1941
telemt_upstream_connect_attempt_total 143675
telemt_upstream_connect_success_total 142550
telemt_upstream_connect_fail_total 1125
telemt_upstream_connect_attempts_per_request{bucket="1"} 143675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 107282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32853
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1125
telemt_me_keepalive_timeout_total 3808
telemt_me_reconnect_attempts_total 162527
telemt_me_reconnect_success_total 31579
telemt_me_reader_eof_total 36499
telemt_me_idle_close_by_peer_total 36499
telemt_me_route_drop_no_conn_total 97304
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 188659
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 39
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
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 35966
telemt_me_refill_failed_total 4086
telemt_me_writer_restored_same_endpoint_total 31562
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4387
telemt_user_connections_total{user="hello"} 291771
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 3046648959 (2.84 GB)
telemt_user_octets_to_client{user="hello"} 91276597735 (85.01 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 153095.9 (42h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 360196
telemt_connections_bad_total 2824
telemt_handshake_timeouts_total 33237
telemt_upstream_connect_attempt_total 40633
telemt_upstream_connect_success_total 40627
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 40633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22001
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3293
telemt_me_reconnect_attempts_total 34197
telemt_me_reconnect_success_total 32930
telemt_me_reader_eof_total 35381
telemt_me_idle_close_by_peer_total 35381
telemt_me_route_drop_no_conn_total 128333
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 311613
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
telemt_pool_swap_total 144
telemt_me_writer_removed_unexpected_total 33319
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 32910
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 389
telemt_user_connections_total{user="hello"} 311464
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 12617474436 (11.75 GB)
telemt_user_octets_to_client{user="hello"} 127063901312 (118.34 GB)
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 153071.6 (42h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 461673
telemt_connections_bad_total 15375
telemt_handshake_timeouts_total 4356
telemt_upstream_connect_attempt_total 69414
telemt_upstream_connect_success_total 58952
telemt_upstream_connect_fail_total 10462
telemt_upstream_connect_attempts_per_request{bucket="1"} 69414
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23023
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 323
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10462
telemt_me_keepalive_timeout_total 5097
telemt_me_reconnect_attempts_total 138328
telemt_me_reconnect_success_total 32288
telemt_me_reader_eof_total 36545
telemt_me_idle_close_by_peer_total 36537
telemt_me_route_drop_no_conn_total 163288
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 391411
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1708
telemt_desync_full_logged_total 501
telemt_desync_suppressed_total 1207
telemt_desync_frames_bucket_total{bucket="1_2"} 400
telemt_desync_frames_bucket_total{bucket="3_10"} 646
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 35987
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 32278
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3699
telemt_user_connections_total{user="hello"} 410253
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 9079745451 (8.46 GB)
telemt_user_octets_to_client{user="hello"} 158232347168 (147.37 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 103243.2 (28h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 172463
telemt_connections_bad_total 25028
telemt_handshake_timeouts_total 1558
telemt_upstream_connect_attempt_total 37722
telemt_upstream_connect_success_total 37378
telemt_upstream_connect_fail_total 344
telemt_upstream_connect_attempts_per_request{bucket="1"} 37722
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18285
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 344
telemt_me_keepalive_timeout_total 1398
telemt_me_reconnect_attempts_total 40758
telemt_me_reconnect_success_total 27343
telemt_me_reader_eof_total 29249
telemt_me_idle_close_by_peer_total 29249
telemt_me_route_drop_no_conn_total 51348
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 136087
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 619
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 474
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 28008
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 27325
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 665
telemt_user_connections_total{user="hello"} 140872
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 1959302689 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 64872979079 (60.42 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 153027.8 (42h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 886788
telemt_connections_bad_total 27706
telemt_handshake_timeouts_total 25331
telemt_upstream_connect_attempt_total 31663
telemt_upstream_connect_success_total 31494
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 31663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16714
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_keepalive_timeout_total 3497
telemt_me_reconnect_attempts_total 28594
telemt_me_reconnect_success_total 23927
telemt_me_reader_eof_total 25639
telemt_me_idle_close_by_peer_total 25636
telemt_me_route_drop_no_conn_total 422451
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 828841
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 708
telemt_desync_full_logged_total 231
telemt_desync_suppressed_total 477
telemt_desync_frames_bucket_total{bucket="1_2"} 253
telemt_desync_frames_bucket_total{bucket="3_10"} 231
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 142
telemt_me_writer_removed_unexpected_total 24385
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 23920
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 458
telemt_user_connections_total{user="hello"} 801598
telemt_user_connections_current{user="hello"} 218
telemt_user_octets_from_client{user="hello"} 14236143176 (13.26 GB)
telemt_user_octets_to_client{user="hello"} 408942972332 (380.86 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 32
```