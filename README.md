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

# Server Metrics 2026-03-14 09:09:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 178596.5 (49h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 690319
telemt_connections_bad_total 32607
telemt_handshake_timeouts_total 13426
telemt_upstream_connect_attempt_total 45329
telemt_upstream_connect_success_total 45098
telemt_upstream_connect_fail_total 231
telemt_upstream_connect_attempts_per_request{bucket="1"} 45329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24291
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 231
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5856
telemt_me_reconnect_attempts_total 40517
telemt_me_reconnect_success_total 35816
telemt_me_reader_eof_total 38300
telemt_me_idle_close_by_peer_total 38299
telemt_me_route_drop_no_conn_total 228228
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 590025
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2293
telemt_desync_full_logged_total 777
telemt_desync_suppressed_total 1516
telemt_desync_frames_bucket_total{bucket="1_2"} 498
telemt_desync_frames_bucket_total{bucket="3_10"} 836
telemt_desync_frames_bucket_total{bucket="gt_10"} 959
telemt_pool_swap_total 165
telemt_me_writer_removed_unexpected_total 36346
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 35796
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 530
telemt_user_connections_total{user="hello"} 589908
telemt_user_connections_current{user="hello"} 389
telemt_user_octets_from_client{user="hello"} 17107564926 (15.93 GB)
telemt_user_octets_to_client{user="hello"} 283689745688 (264.21 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 178490.4 (49h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 347522
telemt_connections_bad_total 2787
telemt_handshake_timeouts_total 3037
telemt_upstream_connect_attempt_total 152932
telemt_upstream_connect_success_total 151596
telemt_upstream_connect_fail_total 1336
telemt_upstream_connect_attempts_per_request{bucket="1"} 152932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38130
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2444
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1336
telemt_me_keepalive_timeout_total 5363
telemt_me_reconnect_attempts_total 183576
telemt_me_reconnect_success_total 39387
telemt_me_reader_eof_total 44945
telemt_me_idle_close_by_peer_total 44945
telemt_me_route_drop_no_conn_total 117516
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 224812
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 44
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
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 44271
telemt_me_refill_failed_total 4499
telemt_me_writer_restored_same_endpoint_total 39370
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4884
telemt_user_connections_total{user="hello"} 327918
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 3400309547 (3.17 GB)
telemt_user_octets_to_client{user="hello"} 105506565231 (98.26 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 178454.1 (49h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 404331
telemt_connections_bad_total 3200
telemt_handshake_timeouts_total 35610
telemt_upstream_connect_attempt_total 47392
telemt_upstream_connect_success_total 47383
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 47392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25614
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3657
telemt_me_reconnect_attempts_total 39732
telemt_me_reconnect_success_total 38433
telemt_me_reader_eof_total 41311
telemt_me_idle_close_by_peer_total 41311
telemt_me_route_drop_no_conn_total 146371
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 351298
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 136
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 168
telemt_me_writer_removed_unexpected_total 38897
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 38412
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 351022
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 13714140288 (12.77 GB)
telemt_user_octets_to_client{user="hello"} 152178921636 (141.73 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 178429.5 (49h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 508510
telemt_connections_bad_total 16444
telemt_handshake_timeouts_total 4635
telemt_upstream_connect_attempt_total 77515
telemt_upstream_connect_success_total 66869
telemt_upstream_connect_fail_total 10646
telemt_upstream_connect_attempts_per_request{bucket="1"} 77515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27288
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 347
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10646
telemt_me_keepalive_timeout_total 5532
telemt_me_reconnect_attempts_total 150061
telemt_me_reconnect_success_total 38937
telemt_me_reader_eof_total 43658
telemt_me_idle_close_by_peer_total 43650
telemt_me_route_drop_no_conn_total 184270
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 434604
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1936
telemt_desync_full_logged_total 572
telemt_desync_suppressed_total 1364
telemt_desync_frames_bucket_total{bucket="1_2"} 452
telemt_desync_frames_bucket_total{bucket="3_10"} 750
telemt_desync_frames_bucket_total{bucket="gt_10"} 734
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 42854
telemt_me_refill_failed_total 3465
telemt_me_writer_restored_same_endpoint_total 38927
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3917
telemt_user_connections_total{user="hello"} 453484
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 9786523363 (9.11 GB)
telemt_user_octets_to_client{user="hello"} 189638478088 (176.61 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 128601.0 (35h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 212047
telemt_connections_bad_total 32689
telemt_handshake_timeouts_total 1801
telemt_upstream_connect_attempt_total 45314
telemt_upstream_connect_success_total 44877
telemt_upstream_connect_fail_total 437
telemt_upstream_connect_attempts_per_request{bucket="1"} 45314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22306
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 437
telemt_me_keepalive_timeout_total 2648
telemt_me_reconnect_attempts_total 48323
telemt_me_reconnect_success_total 33603
telemt_me_reader_eof_total 35946
telemt_me_idle_close_by_peer_total 35946
telemt_me_route_drop_no_conn_total 63879
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166922
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 724
telemt_desync_full_logged_total 175
telemt_desync_suppressed_total 549
telemt_desync_frames_bucket_total{bucket="1_2"} 125
telemt_desync_frames_bucket_total{bucket="3_10"} 342
telemt_desync_frames_bucket_total{bucket="gt_10"} 257
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 34367
telemt_me_refill_failed_total 456
telemt_me_writer_restored_same_endpoint_total 33585
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 764
telemt_user_connections_total{user="hello"} 171683
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 2507969709 (2.34 GB)
telemt_user_octets_to_client{user="hello"} 81332420563 (75.75 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 178385.5 (49h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1028557
telemt_connections_bad_total 36402
telemt_handshake_timeouts_total 26551
telemt_upstream_connect_attempt_total 37174
telemt_upstream_connect_success_total 36975
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 37174
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19509
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_keepalive_timeout_total 4825
telemt_me_reconnect_attempts_total 32823
telemt_me_reconnect_success_total 28139
telemt_me_reader_eof_total 30183
telemt_me_idle_close_by_peer_total 30180
telemt_me_route_drop_no_conn_total 482789
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 953275
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 792
telemt_desync_full_logged_total 259
telemt_desync_suppressed_total 533
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 264
telemt_desync_frames_bucket_total{bucket="gt_10"} 268
telemt_pool_swap_total 168
telemt_me_writer_removed_unexpected_total 28638
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 28132
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 499
telemt_user_connections_total{user="hello"} 925896
telemt_user_connections_current{user="hello"} 390
telemt_user_octets_from_client{user="hello"} 17007443852 (15.84 GB)
telemt_user_octets_to_client{user="hello"} 460855226928 (429.20 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 62
```