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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-19 04:56:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 25709.9 (7h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 359384
telemt_connections_bad_total 37600
telemt_connections_current 906
telemt_connections_me_current 906
telemt_handshake_timeouts_total 20210
telemt_upstream_connect_attempt_total 5021
telemt_upstream_connect_success_total 4938
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 5021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2522
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3667
telemt_me_reconnect_success_total 3650
telemt_me_reader_eof_total 3847
telemt_me_idle_close_by_peer_total 3846
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 92940
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 263992
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1821
telemt_desync_full_logged_total 501
telemt_desync_suppressed_total 1320
telemt_desync_frames_bucket_total{bucket="1_2"} 674
telemt_desync_frames_bucket_total{bucket="3_10"} 735
telemt_desync_frames_bucket_total{bucket="gt_10"} 412
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 3679
telemt_me_writer_restored_same_endpoint_total 3633
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 261242
telemt_user_connections_current{user="hello"} 906
telemt_user_octets_from_client{user="hello"} 3117825092 (2.90 GB)
telemt_user_octets_to_client{user="hello"} 82956830876 (77.26 GB)
telemt_user_unique_ips_current{user="hello"} 364
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 25714.0 (7h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 685867
telemt_connections_bad_total 42510
telemt_connections_current 2688
telemt_connections_me_current 2688
telemt_handshake_timeouts_total 21362
telemt_upstream_connect_attempt_total 4842
telemt_upstream_connect_success_total 4752
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 4842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2451
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_reconnect_attempts_total 3473
telemt_me_reconnect_success_total 3456
telemt_me_reader_eof_total 3647
telemt_me_idle_close_by_peer_total 3647
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 206725
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 568411
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2298
telemt_desync_full_logged_total 776
telemt_desync_suppressed_total 1522
telemt_desync_frames_bucket_total{bucket="1_2"} 453
telemt_desync_frames_bucket_total{bucket="3_10"} 855
telemt_desync_frames_bucket_total{bucket="gt_10"} 990
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 3515
telemt_me_writer_restored_same_endpoint_total 3438
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 568325
telemt_user_connections_current{user="hello"} 2688
telemt_user_octets_from_client{user="hello"} 15242556048 (14.20 GB)
telemt_user_octets_to_client{user="hello"} 249559945708 (232.42 GB)
telemt_user_unique_ips_current{user="hello"} 984
telemt_user_unique_ips_recent_window{user="hello"} 346
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 25711.5 (7h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 579660
telemt_connections_bad_total 109640
telemt_connections_current 2255
telemt_connections_me_current 2255
telemt_handshake_timeouts_total 20081
telemt_upstream_connect_attempt_total 4746
telemt_upstream_connect_success_total 4746
telemt_upstream_connect_attempts_per_request{bucket="1"} 4746
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2417
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2322
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3459
telemt_me_reconnect_success_total 3448
telemt_me_reader_eof_total 3646
telemt_me_idle_close_by_peer_total 3646
telemt_me_route_drop_no_conn_total 171713
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 417626
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2225
telemt_desync_full_logged_total 727
telemt_desync_suppressed_total 1498
telemt_desync_frames_bucket_total{bucket="1_2"} 336
telemt_desync_frames_bucket_total{bucket="3_10"} 783
telemt_desync_frames_bucket_total{bucket="gt_10"} 1106
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 3505
telemt_me_writer_restored_same_endpoint_total 3432
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 417609
telemt_user_connections_current{user="hello"} 2255
telemt_user_octets_from_client{user="hello"} 9086225332 (8.46 GB)
telemt_user_octets_to_client{user="hello"} 262770278596 (244.72 GB)
telemt_user_unique_ips_current{user="hello"} 797
telemt_user_unique_ips_recent_window{user="hello"} 295
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 25764.5 (7h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 678095
telemt_connections_bad_total 85169
telemt_connections_current 1637
telemt_connections_me_current 1637
telemt_handshake_timeouts_total 15157
telemt_upstream_connect_attempt_total 4592
telemt_upstream_connect_success_total 4592
telemt_upstream_connect_attempts_per_request{bucket="1"} 4592
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2258
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 3313
telemt_me_reconnect_success_total 3298
telemt_me_reader_eof_total 3480
telemt_me_idle_close_by_peer_total 3479
telemt_me_route_drop_no_conn_total 169281
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 411318
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1287
telemt_desync_full_logged_total 470
telemt_desync_suppressed_total 817
telemt_desync_frames_bucket_total{bucket="1_2"} 237
telemt_desync_frames_bucket_total{bucket="3_10"} 551
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 3337
telemt_me_writer_restored_same_endpoint_total 3274
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 411085
telemt_user_connections_current{user="hello"} 1637
telemt_user_octets_from_client{user="hello"} 6015788816 (5.60 GB)
telemt_user_octets_to_client{user="hello"} 157903992676 (147.06 GB)
telemt_user_unique_ips_current{user="hello"} 657
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 25707.7 (7h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 756400
telemt_connections_bad_total 207071
telemt_connections_current 2011
telemt_connections_me_current 2011
telemt_handshake_timeouts_total 20793
telemt_upstream_connect_attempt_total 4716
telemt_upstream_connect_success_total 4687
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 4716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2319
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_reconnect_attempts_total 3408
telemt_me_reconnect_success_total 3388
telemt_me_reader_eof_total 3581
telemt_me_idle_close_by_peer_total 3581
telemt_me_route_drop_no_conn_total 185806
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 446790
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2016
telemt_desync_full_logged_total 767
telemt_desync_suppressed_total 1249
telemt_desync_frames_bucket_total{bucket="1_2"} 466
telemt_desync_frames_bucket_total{bucket="3_10"} 850
telemt_desync_frames_bucket_total{bucket="gt_10"} 700
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 3421
telemt_me_writer_restored_same_endpoint_total 3364
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 446714
telemt_user_connections_current{user="hello"} 2011
telemt_user_octets_from_client{user="hello"} 13601434912 (12.67 GB)
telemt_user_octets_to_client{user="hello"} 258303800896 (240.56 GB)
telemt_user_unique_ips_current{user="hello"} 786
telemt_user_unique_ips_recent_window{user="hello"} 278
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 25719.4 (7h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133756
telemt_connections_bad_total 10400
telemt_connections_current 503
telemt_connections_me_current 503
telemt_handshake_timeouts_total 602
telemt_upstream_connect_attempt_total 7064
telemt_upstream_connect_success_total 6875
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 7064
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3271
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3604
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_reconnect_attempts_total 7424
telemt_me_reconnect_success_total 5581
telemt_me_reader_eof_total 5860
telemt_me_idle_close_by_peer_total 5860
telemt_me_route_drop_no_conn_total 54162
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117413
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 138
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 87
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 34
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 5655
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 5551
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 117405
telemt_user_connections_current{user="hello"} 503
telemt_user_octets_from_client{user="hello"} 2103913792 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 73597676748 (68.54 GB)
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 25710.3 (7h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 441628
telemt_connections_bad_total 47655
telemt_connections_current 1948
telemt_connections_me_current 1948
telemt_handshake_timeouts_total 22937
telemt_upstream_connect_attempt_total 5288
telemt_upstream_connect_success_total 5288
telemt_upstream_connect_attempts_per_request{bucket="1"} 5288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2473
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 4010
telemt_me_reconnect_success_total 3998
telemt_me_reader_eof_total 4221
telemt_me_idle_close_by_peer_total 4221
telemt_me_route_drop_no_conn_total 123958
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 357435
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1931
telemt_desync_full_logged_total 728
telemt_desync_suppressed_total 1203
telemt_desync_frames_bucket_total{bucket="1_2"} 394
telemt_desync_frames_bucket_total{bucket="3_10"} 740
telemt_desync_frames_bucket_total{bucket="gt_10"} 797
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4043
telemt_me_writer_restored_same_endpoint_total 3983
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 357447
telemt_user_connections_current{user="hello"} 1948
telemt_user_octets_from_client{user="hello"} 4398938864 (4.10 GB)
telemt_user_octets_to_client{user="hello"} 210000830700 (195.58 GB)
telemt_user_unique_ips_current{user="hello"} 651
telemt_user_unique_ips_recent_window{user="hello"} 216
```