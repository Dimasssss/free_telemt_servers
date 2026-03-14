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

# Server Metrics 2026-03-14 09:20:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 179206.6 (49h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 693279
telemt_connections_bad_total 32607
telemt_handshake_timeouts_total 13528
telemt_upstream_connect_attempt_total 45433
telemt_upstream_connect_success_total 45202
telemt_upstream_connect_fail_total 231
telemt_upstream_connect_attempts_per_request{bucket="1"} 45433
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20696
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24354
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 231
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5866
telemt_me_reconnect_attempts_total 40584
telemt_me_reconnect_success_total 35884
telemt_me_reader_eof_total 38367
telemt_me_idle_close_by_peer_total 38366
telemt_me_route_drop_no_conn_total 229213
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 592760
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2360
telemt_desync_full_logged_total 785
telemt_desync_suppressed_total 1575
telemt_desync_frames_bucket_total{bucket="1_2"} 502
telemt_desync_frames_bucket_total{bucket="3_10"} 867
telemt_desync_frames_bucket_total{bucket="gt_10"} 991
telemt_pool_swap_total 165
telemt_me_writer_removed_unexpected_total 36413
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 35864
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 529
telemt_user_connections_total{user="hello"} 592644
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 17194743346 (16.01 GB)
telemt_user_octets_to_client{user="hello"} 285185560304 (265.60 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 179100.1 (49h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 348864
telemt_connections_bad_total 2787
telemt_handshake_timeouts_total 3040
telemt_upstream_connect_attempt_total 153070
telemt_upstream_connect_success_total 151734
telemt_upstream_connect_fail_total 1336
telemt_upstream_connect_attempts_per_request{bucket="1"} 153070
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38198
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2444
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1336
telemt_me_keepalive_timeout_total 5365
telemt_me_reconnect_attempts_total 183714
telemt_me_reconnect_success_total 39525
telemt_me_reader_eof_total 45082
telemt_me_idle_close_by_peer_total 45082
telemt_me_route_drop_no_conn_total 118470
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 226119
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
telemt_me_writer_removed_unexpected_total 44409
telemt_me_refill_failed_total 4499
telemt_me_writer_restored_same_endpoint_total 39508
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4884
telemt_user_connections_total{user="hello"} 329223
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 3407143215 (3.17 GB)
telemt_user_octets_to_client{user="hello"} 105696928939 (98.44 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 179064.2 (49h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 405564
telemt_connections_bad_total 3200
telemt_handshake_timeouts_total 35633
telemt_upstream_connect_attempt_total 47496
telemt_upstream_connect_success_total 47487
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 47496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25675
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3676
telemt_me_reconnect_attempts_total 39836
telemt_me_reconnect_success_total 38538
telemt_me_reader_eof_total 41416
telemt_me_idle_close_by_peer_total 41416
telemt_me_route_drop_no_conn_total 146997
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 352438
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
telemt_me_writer_removed_unexpected_total 39002
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 38517
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 352163
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 13733711828 (12.79 GB)
telemt_user_octets_to_client{user="hello"} 154403654800 (143.80 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 179039.3 (49h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 510200
telemt_connections_bad_total 16444
telemt_handshake_timeouts_total 4646
telemt_upstream_connect_attempt_total 77665
telemt_upstream_connect_success_total 67019
telemt_upstream_connect_fail_total 10646
telemt_upstream_connect_attempts_per_request{bucket="1"} 77665
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27385
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 347
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10646
telemt_me_keepalive_timeout_total 5546
telemt_me_reconnect_attempts_total 150211
telemt_me_reconnect_success_total 39087
telemt_me_reader_eof_total 43809
telemt_me_idle_close_by_peer_total 43801
telemt_me_route_drop_no_conn_total 185051
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 436209
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1942
telemt_desync_full_logged_total 573
telemt_desync_suppressed_total 1369
telemt_desync_frames_bucket_total{bucket="1_2"} 452
telemt_desync_frames_bucket_total{bucket="3_10"} 751
telemt_desync_frames_bucket_total{bucket="gt_10"} 739
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 43005
telemt_me_refill_failed_total 3465
telemt_me_writer_restored_same_endpoint_total 39077
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3918
telemt_user_connections_total{user="hello"} 455092
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 9822017811 (9.15 GB)
telemt_user_octets_to_client{user="hello"} 190116564744 (177.06 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 129210.8 (35h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213357
telemt_connections_bad_total 32958
telemt_handshake_timeouts_total 1827
telemt_upstream_connect_attempt_total 45611
telemt_upstream_connect_success_total 45167
telemt_upstream_connect_fail_total 444
telemt_upstream_connect_attempts_per_request{bucket="1"} 45611
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22440
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 444
telemt_me_keepalive_timeout_total 2649
telemt_me_reconnect_attempts_total 48567
telemt_me_reconnect_success_total 33845
telemt_me_reader_eof_total 36192
telemt_me_idle_close_by_peer_total 36192
telemt_me_route_drop_no_conn_total 64222
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167894
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 726
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 550
telemt_desync_frames_bucket_total{bucket="1_2"} 125
telemt_desync_frames_bucket_total{bucket="3_10"} 343
telemt_desync_frames_bucket_total{bucket="gt_10"} 258
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 34613
telemt_me_refill_failed_total 456
telemt_me_writer_restored_same_endpoint_total 33827
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 768
telemt_user_connections_total{user="hello"} 172655
telemt_user_connections_current{user="hello"} 82
telemt_user_octets_from_client{user="hello"} 2627359641 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 81664061539 (76.06 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 178995.4 (49h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1032708
telemt_connections_bad_total 36843
telemt_handshake_timeouts_total 26673
telemt_upstream_connect_attempt_total 37314
telemt_upstream_connect_success_total 37115
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 37314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19572
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_keepalive_timeout_total 4828
telemt_me_reconnect_attempts_total 32963
telemt_me_reconnect_success_total 28278
telemt_me_reader_eof_total 30323
telemt_me_idle_close_by_peer_total 30320
telemt_me_route_drop_no_conn_total 484289
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 956776
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 798
telemt_desync_full_logged_total 262
telemt_desync_suppressed_total 536
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 266
telemt_desync_frames_bucket_total{bucket="gt_10"} 272
telemt_pool_swap_total 168
telemt_me_writer_removed_unexpected_total 28778
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 28271
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 500
telemt_user_connections_total{user="hello"} 929396
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 17055433248 (15.88 GB)
telemt_user_octets_to_client{user="hello"} 462531053936 (430.77 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 72
```