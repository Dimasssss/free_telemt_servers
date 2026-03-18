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

# Server Metrics 2026-03-18 02:23:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 113868.6 (31h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1317398
telemt_connections_bad_total 10145
telemt_handshake_timeouts_total 33120
telemt_upstream_connect_attempt_total 25331
telemt_upstream_connect_success_total 24827
telemt_upstream_connect_fail_total 504
telemt_upstream_connect_attempts_per_request{bucket="1"} 25331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12733
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11886
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 504
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 33999
telemt_me_reconnect_success_total 16859
telemt_me_reader_eof_total 18300
telemt_me_idle_close_by_peer_total 18299
telemt_me_route_drop_no_conn_total 569558
telemt_me_route_drop_channel_closed_total 158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1212437
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7713
telemt_desync_full_logged_total 2285
telemt_desync_suppressed_total 5428
telemt_desync_frames_bucket_total{bucket="1_2"} 2065
telemt_desync_frames_bucket_total{bucket="3_10"} 2936
telemt_desync_frames_bucket_total{bucket="gt_10"} 2712
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 17644
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 16837
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 785
telemt_user_connections_total{user="hello"} 1206649
telemt_user_connections_current{user="hello"} 592
telemt_user_octets_from_client{user="hello"} 24339537163 (22.67 GB)
telemt_user_octets_to_client{user="hello"} 425003996479 (395.82 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 248
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 114120.0 (31h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1389357
telemt_connections_bad_total 64218
telemt_handshake_timeouts_total 47085
telemt_upstream_connect_attempt_total 468132
telemt_upstream_connect_success_total 466556
telemt_upstream_connect_fail_total 1576
telemt_upstream_connect_attempts_per_request{bucket="1"} 468132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33316
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43356
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1576
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 123397
telemt_me_reconnect_success_total 17957
telemt_me_reader_eof_total 20129
telemt_me_idle_close_by_peer_total 20116
telemt_me_route_drop_no_conn_total 358103
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 765550
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3591
telemt_desync_full_logged_total 1222
telemt_desync_suppressed_total 2369
telemt_desync_frames_bucket_total{bucket="1_2"} 710
telemt_desync_frames_bucket_total{bucket="3_10"} 1493
telemt_desync_frames_bucket_total{bucket="gt_10"} 1388
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 19522
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 17939
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1565
telemt_user_connections_total{user="hello"} 1207901
telemt_user_connections_current{user="hello"} 659
telemt_user_octets_from_client{user="hello"} 16318260061 (15.20 GB)
telemt_user_octets_to_client{user="hello"} 423846270694 (394.74 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 113895.9 (31h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 839332
telemt_connections_bad_total 58305
telemt_handshake_timeouts_total 24562
telemt_upstream_connect_attempt_total 26616
telemt_upstream_connect_success_total 26464
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 26616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14239
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 41435
telemt_me_reconnect_success_total 20743
telemt_me_reader_eof_total 22571
telemt_me_idle_close_by_peer_total 22564
telemt_me_route_drop_no_conn_total 331707
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 705854
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2225
telemt_desync_full_logged_total 721
telemt_desync_suppressed_total 1504
telemt_desync_frames_bucket_total{bucket="1_2"} 634
telemt_desync_frames_bucket_total{bucket="3_10"} 863
telemt_desync_frames_bucket_total{bucket="gt_10"} 728
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 21667
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 20731
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 924
telemt_user_connections_total{user="hello"} 703972
telemt_user_connections_current{user="hello"} 481
telemt_user_octets_from_client{user="hello"} 43958633876 (40.94 GB)
telemt_user_octets_to_client{user="hello"} 312789850792 (291.31 GB)
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 113955.5 (31h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1316486
telemt_connections_bad_total 59018
telemt_handshake_timeouts_total 22097
telemt_upstream_connect_attempt_total 89392
telemt_upstream_connect_success_total 86979
telemt_upstream_connect_fail_total 2413
telemt_upstream_connect_attempts_per_request{bucket="1"} 89392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72677
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13905
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 367
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2413
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 36931
telemt_me_reconnect_success_total 16535
telemt_me_reader_eof_total 18218
telemt_me_idle_close_by_peer_total 18216
telemt_me_route_drop_no_conn_total 541484
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1069408
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3981
telemt_desync_full_logged_total 1317
telemt_desync_suppressed_total 2664
telemt_desync_frames_bucket_total{bucket="1_2"} 972
telemt_desync_frames_bucket_total{bucket="3_10"} 1671
telemt_desync_frames_bucket_total{bucket="gt_10"} 1338
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 17486
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 16524
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 951
telemt_user_connections_total{user="hello"} 1132782
telemt_user_connections_current{user="hello"} 547
telemt_user_octets_from_client{user="hello"} 17778017686 (16.56 GB)
telemt_user_octets_to_client{user="hello"} 535644343966 (498.86 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 113927.5 (31h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 874992
telemt_connections_bad_total 100798
telemt_handshake_timeouts_total 6876
telemt_upstream_connect_attempt_total 46166
telemt_upstream_connect_success_total 45537
telemt_upstream_connect_fail_total 629
telemt_upstream_connect_attempts_per_request{bucket="1"} 46166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16674
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 416
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 629
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 58337
telemt_me_reconnect_success_total 23375
telemt_me_reader_eof_total 25342
telemt_me_idle_close_by_peer_total 25339
telemt_me_route_drop_no_conn_total 279698
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 707811
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3230
telemt_desync_full_logged_total 968
telemt_desync_suppressed_total 2262
telemt_desync_frames_bucket_total{bucket="1_2"} 1008
telemt_desync_frames_bucket_total{bucket="3_10"} 1289
telemt_desync_frames_bucket_total{bucket="gt_10"} 933
telemt_pool_swap_total 58
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24841
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 23367
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1466
telemt_user_connections_total{user="hello"} 724371
telemt_user_connections_current{user="hello"} 501
telemt_user_octets_from_client{user="hello"} 13923110704 (12.97 GB)
telemt_user_octets_to_client{user="hello"} 358053649748 (333.46 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 114088.3 (31h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1123971
telemt_connections_bad_total 120772
telemt_handshake_timeouts_total 9871
telemt_upstream_connect_attempt_total 22705
telemt_upstream_connect_success_total 22575
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 22705
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11632
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 28191
telemt_me_reconnect_success_total 16902
telemt_me_reader_eof_total 18330
telemt_me_idle_close_by_peer_total 18328
telemt_me_route_drop_no_conn_total 774073
telemt_me_route_drop_channel_closed_total 89
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1098076
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2106
telemt_desync_full_logged_total 737
telemt_desync_suppressed_total 1369
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 802
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 101
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 17522
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 16888
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 620
telemt_user_connections_total{user="hello"} 922409
telemt_user_connections_current{user="hello"} 416
telemt_user_octets_from_client{user="hello"} 14924964640 (13.90 GB)
telemt_user_octets_to_client{user="hello"} 402480368940 (374.84 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 61855.6 (17h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 427026
telemt_connections_bad_total 44730
telemt_handshake_timeouts_total 11196
telemt_upstream_connect_attempt_total 22836
telemt_upstream_connect_success_total 22616
telemt_upstream_connect_fail_total 220
telemt_upstream_connect_attempts_per_request{bucket="1"} 22836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12122
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10398
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 220
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 30990
telemt_me_reconnect_success_total 19383
telemt_me_reader_eof_total 20490
telemt_me_idle_close_by_peer_total 20490
telemt_me_seq_mismatch_total 28
telemt_me_route_drop_no_conn_total 105633
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 309531
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 32
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1355
telemt_desync_full_logged_total 428
telemt_desync_suppressed_total 927
telemt_desync_frames_bucket_total{bucket="1_2"} 227
telemt_desync_frames_bucket_total{bucket="3_10"} 608
telemt_desync_frames_bucket_total{bucket="gt_10"} 520
telemt_pool_swap_total 40
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19961
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 19345
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 578
telemt_user_connections_total{user="hello"} 309467
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 22599274233 (21.05 GB)
telemt_user_octets_to_client{user="hello"} 259890147574 (242.04 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 35
```