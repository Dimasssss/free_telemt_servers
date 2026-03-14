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

# Server Metrics 2026-03-14 05:05:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 163935.4 (45h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 634367
telemt_connections_bad_total 32286
telemt_handshake_timeouts_total 12971
telemt_upstream_connect_attempt_total 41896
telemt_upstream_connect_success_total 41681
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 41896
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22495
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5562
telemt_me_reconnect_attempts_total 37793
telemt_me_reconnect_success_total 33108
telemt_me_reader_eof_total 35393
telemt_me_idle_close_by_peer_total 35392
telemt_me_route_drop_no_conn_total 206342
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 536999
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1877
telemt_desync_full_logged_total 632
telemt_desync_suppressed_total 1245
telemt_desync_frames_bucket_total{bucket="1_2"} 404
telemt_desync_frames_bucket_total{bucket="3_10"} 691
telemt_desync_frames_bucket_total{bucket="gt_10"} 782
telemt_pool_swap_total 151
telemt_me_writer_removed_unexpected_total 33615
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 33088
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 507
telemt_user_connections_total{user="hello"} 536883
telemt_user_connections_current{user="hello"} 278
telemt_user_octets_from_client{user="hello"} 15854207782 (14.77 GB)
telemt_user_octets_to_client{user="hello"} 259844630288 (242.00 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 163828.4 (45h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 320382
telemt_connections_bad_total 2280
telemt_handshake_timeouts_total 2332
telemt_upstream_connect_attempt_total 147715
telemt_upstream_connect_success_total 146513
telemt_upstream_connect_fail_total 1202
telemt_upstream_connect_attempts_per_request{bucket="1"} 147715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 108970
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35125
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2418
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1202
telemt_me_keepalive_timeout_total 3887
telemt_me_reconnect_attempts_total 171869
telemt_me_reconnect_success_total 35059
telemt_me_reader_eof_total 40248
telemt_me_idle_close_by_peer_total 40248
telemt_me_route_drop_no_conn_total 101958
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 200338
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 42
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
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 39663
telemt_me_refill_failed_total 4269
telemt_me_writer_restored_same_endpoint_total 35042
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4604
telemt_user_connections_total{user="hello"} 303447
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 3153689255 (2.94 GB)
telemt_user_octets_to_client{user="hello"} 98361877527 (91.61 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 163792.1 (45h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 372631
telemt_connections_bad_total 2956
telemt_handshake_timeouts_total 34889
telemt_upstream_connect_attempt_total 43367
telemt_upstream_connect_success_total 43358
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 43367
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23489
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3401
telemt_me_reconnect_attempts_total 36455
telemt_me_reconnect_success_total 35173
telemt_me_reader_eof_total 37808
telemt_me_idle_close_by_peer_total 37808
telemt_me_route_drop_no_conn_total 133672
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 321872
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
telemt_pool_swap_total 154
telemt_me_writer_removed_unexpected_total 35602
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 35152
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 429
telemt_user_connections_total{user="hello"} 321652
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 12716697280 (11.84 GB)
telemt_user_octets_to_client{user="hello"} 128517206688 (119.69 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 163767.5 (45h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 474319
telemt_connections_bad_total 15599
telemt_handshake_timeouts_total 4412
telemt_upstream_connect_attempt_total 73316
telemt_upstream_connect_success_total 62785
telemt_upstream_connect_fail_total 10531
telemt_upstream_connect_attempts_per_request{bucket="1"} 73316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37331
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25111
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10531
telemt_me_keepalive_timeout_total 5294
telemt_me_reconnect_attempts_total 141660
telemt_me_reconnect_success_total 35610
telemt_me_reader_eof_total 40026
telemt_me_idle_close_by_peer_total 40018
telemt_me_route_drop_no_conn_total 170289
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 402806
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1716
telemt_desync_full_logged_total 505
telemt_desync_suppressed_total 1211
telemt_desync_frames_bucket_total{bucket="1_2"} 404
telemt_desync_frames_bucket_total{bucket="3_10"} 648
telemt_desync_frames_bucket_total{bucket="gt_10"} 664
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 39331
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 35600
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3721
telemt_user_connections_total{user="hello"} 421647
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 9215000143 (8.58 GB)
telemt_user_octets_to_client{user="hello"} 165450136032 (154.09 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 113939.2 (31h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 186574
telemt_connections_bad_total 27003
telemt_handshake_timeouts_total 1658
telemt_upstream_connect_attempt_total 40900
telemt_upstream_connect_success_total 40521
telemt_upstream_connect_fail_total 379
telemt_upstream_connect_attempts_per_request{bucket="1"} 40900
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20045
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 379
telemt_me_keepalive_timeout_total 2405
telemt_me_reconnect_attempts_total 43382
telemt_me_reconnect_success_total 29958
telemt_me_reader_eof_total 32064
telemt_me_idle_close_by_peer_total 32064
telemt_me_route_drop_no_conn_total 55266
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 147892
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 622
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 30646
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 29940
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 688
telemt_user_connections_total{user="hello"} 152645
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 2263041753 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 69572242543 (64.79 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 163723.6 (45h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 931946
telemt_connections_bad_total 31655
telemt_handshake_timeouts_total 25791
telemt_upstream_connect_attempt_total 34009
telemt_upstream_connect_success_total 33825
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 34009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17925
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_timeout_total 4590
telemt_me_reconnect_attempts_total 30413
telemt_me_reconnect_success_total 25741
telemt_me_reader_eof_total 27628
telemt_me_idle_close_by_peer_total 27625
telemt_me_route_drop_no_conn_total 441371
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 867049
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 760
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 154
telemt_me_writer_removed_unexpected_total 26215
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 25734
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 474
telemt_user_connections_total{user="hello"} 839710
telemt_user_connections_current{user="hello"} 351
telemt_user_octets_from_client{user="hello"} 14630710520 (13.63 GB)
telemt_user_octets_to_client{user="hello"} 426273602092 (397.00 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 48
```