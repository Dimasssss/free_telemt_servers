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

# Server Metrics 2026-03-17 14:34:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 71336.7 (19h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 757533
telemt_connections_bad_total 5744
telemt_handshake_timeouts_total 22463
telemt_upstream_connect_attempt_total 17311
telemt_upstream_connect_success_total 16853
telemt_upstream_connect_fail_total 458
telemt_upstream_connect_attempts_per_request{bucket="1"} 17311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7868
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 458
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 22907
telemt_me_reconnect_success_total 10966
telemt_me_reader_eof_total 11893
telemt_me_idle_close_by_peer_total 11892
telemt_me_route_drop_no_conn_total 301393
telemt_me_route_drop_channel_closed_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 686396
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4732
telemt_desync_full_logged_total 1338
telemt_desync_suppressed_total 3394
telemt_desync_frames_bucket_total{bucket="1_2"} 1321
telemt_desync_frames_bucket_total{bucket="3_10"} 1932
telemt_desync_frames_bucket_total{bucket="gt_10"} 1479
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11492
telemt_me_refill_failed_total 368
telemt_me_writer_restored_same_endpoint_total 10944
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 526
telemt_user_connections_total{user="hello"} 688265
telemt_user_connections_current{user="hello"} 1056
telemt_user_octets_from_client{user="hello"} 11579174807 (10.78 GB)
telemt_user_octets_to_client{user="hello"} 230423293147 (214.60 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 347
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 71588.1 (19h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 480514
telemt_connections_bad_total 30982
telemt_handshake_timeouts_total 24195
telemt_upstream_connect_attempt_total 57480
telemt_upstream_connect_success_total 57020
telemt_upstream_connect_fail_total 458
telemt_upstream_connect_attempts_per_request{bucket="1"} 57478
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41672
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11032
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4316
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 458
telemt_me_keepalive_timeout_total 326
telemt_me_reconnect_attempts_total 34511
telemt_me_reconnect_success_total 13385
telemt_me_reader_eof_total 14606
telemt_me_idle_close_by_peer_total 14606
telemt_me_route_drop_no_conn_total 189209
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 362275
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1457
telemt_desync_full_logged_total 456
telemt_desync_suppressed_total 1001
telemt_desync_frames_bucket_total{bucket="1_2"} 327
telemt_desync_frames_bucket_total{bucket="3_10"} 637
telemt_desync_frames_bucket_total{bucket="gt_10"} 493
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14208
telemt_me_refill_failed_total 656
telemt_me_writer_restored_same_endpoint_total 13369
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 823
telemt_user_connections_total{user="hello"} 402218
telemt_user_connections_current{user="hello"} 725
telemt_user_octets_from_client{user="hello"} 4323283033 (4.03 GB)
telemt_user_octets_to_client{user="hello"} 123384215349 (114.91 GB)
telemt_user_msgs_from_client{user="hello"} 545106
telemt_user_msgs_to_client{user="hello"} 1781209
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 71364.0 (19h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 249431
telemt_connections_bad_total 7815
telemt_handshake_timeouts_total 17035
telemt_upstream_connect_attempt_total 18839
telemt_upstream_connect_success_total 18744
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 18839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10272
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 24802
telemt_me_reconnect_success_total 15111
telemt_me_reader_eof_total 16280
telemt_me_idle_close_by_peer_total 16277
telemt_me_route_drop_no_conn_total 107887
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 211580
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 779
telemt_desync_full_logged_total 224
telemt_desync_suppressed_total 555
telemt_desync_frames_bucket_total{bucket="1_2"} 282
telemt_desync_frames_bucket_total{bucket="3_10"} 351
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 15621
telemt_me_refill_failed_total 300
telemt_me_writer_restored_same_endpoint_total 15100
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 211449
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 16592345300 (15.45 GB)
telemt_user_octets_to_client{user="hello"} 54156503548 (50.44 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 71423.3 (19h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 578545
telemt_connections_bad_total 8109
telemt_handshake_timeouts_total 13145
telemt_upstream_connect_attempt_total 16660
telemt_upstream_connect_success_total 16502
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 16660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8269
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8114
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 23921
telemt_me_reconnect_success_total 11858
telemt_me_reader_eof_total 12888
telemt_me_idle_close_by_peer_total 12887
telemt_me_route_drop_no_conn_total 210957
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 496346
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1708
telemt_desync_full_logged_total 581
telemt_desync_suppressed_total 1127
telemt_desync_frames_bucket_total{bucket="1_2"} 438
telemt_desync_frames_bucket_total{bucket="3_10"} 760
telemt_desync_frames_bucket_total{bucket="gt_10"} 510
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12442
telemt_me_refill_failed_total 372
telemt_me_writer_restored_same_endpoint_total 11849
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 584
telemt_user_connections_total{user="hello"} 497174
telemt_user_connections_current{user="hello"} 719
telemt_user_octets_from_client{user="hello"} 6253033790 (5.82 GB)
telemt_user_octets_to_client{user="hello"} 160516025791 (149.49 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 71395.3 (19h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 276892
telemt_connections_bad_total 56915
telemt_handshake_timeouts_total 3549
telemt_upstream_connect_attempt_total 20894
telemt_upstream_connect_success_total 20433
telemt_upstream_connect_fail_total 461
telemt_upstream_connect_attempts_per_request{bucket="1"} 20894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10938
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 285
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 461
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 38310
telemt_me_reconnect_success_total 16433
telemt_me_reader_eof_total 17704
telemt_me_idle_close_by_peer_total 17702
telemt_me_route_drop_no_conn_total 78160
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 204879
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1112
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 877
telemt_desync_frames_bucket_total{bucket="1_2"} 555
telemt_desync_frames_bucket_total{bucket="3_10"} 428
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 17392
telemt_me_refill_failed_total 679
telemt_me_writer_restored_same_endpoint_total 16425
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 959
telemt_user_connections_total{user="hello"} 205346
telemt_user_connections_current{user="hello"} 290
telemt_user_octets_from_client{user="hello"} 2630899231 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 74198578927 (69.10 GB)
telemt_user_msgs_from_client{user="hello"} 1159
telemt_user_msgs_to_client{user="hello"} 2341
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 71557.6 (19h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 666022
telemt_connections_bad_total 53978
telemt_handshake_timeouts_total 6577
telemt_upstream_connect_attempt_total 14297
telemt_upstream_connect_success_total 14221
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 14297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7008
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7190
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 20913
telemt_me_reconnect_success_total 10632
telemt_me_reader_eof_total 11598
telemt_me_idle_close_by_peer_total 11598
telemt_me_route_drop_no_conn_total 466685
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 667100
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 902
telemt_desync_full_logged_total 338
telemt_desync_suppressed_total 564
telemt_desync_frames_bucket_total{bucket="1_2"} 228
telemt_desync_frames_bucket_total{bucket="3_10"} 355
telemt_desync_frames_bucket_total{bucket="gt_10"} 319
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 11116
telemt_me_refill_failed_total 319
telemt_me_writer_restored_same_endpoint_total 10618
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 484
telemt_user_connections_total{user="hello"} 571260
telemt_user_connections_current{user="hello"} 958
telemt_user_octets_from_client{user="hello"} 8523745612 (7.94 GB)
telemt_user_octets_to_client{user="hello"} 257038590528 (239.39 GB)
telemt_user_unique_ips_current{user="hello"} 343
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 19323.4 (5h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15523
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 308
telemt_upstream_connect_attempt_total 10730
telemt_upstream_connect_success_total 10646
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 10730
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5840
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4797
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 21039
telemt_me_reconnect_success_total 9494
telemt_me_reader_eof_total 10056
telemt_me_idle_close_by_peer_total 10056
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 5491
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14754
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 9947
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 9479
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 453
telemt_user_connections_total{user="hello"} 14855
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 438115397 (417.82 MB)
telemt_user_octets_to_client{user="hello"} 22819063950 (21.25 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 9
```