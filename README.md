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

# Server Metrics 2026-03-18 01:52:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 112035.8 (31h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1299070
telemt_connections_bad_total 9665
telemt_handshake_timeouts_total 32559
telemt_upstream_connect_attempt_total 24975
telemt_upstream_connect_success_total 24472
telemt_upstream_connect_fail_total 503
telemt_upstream_connect_attempts_per_request{bucket="1"} 24975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11713
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 503
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 33733
telemt_me_reconnect_success_total 16594
telemt_me_reader_eof_total 18017
telemt_me_idle_close_by_peer_total 18016
telemt_me_route_drop_no_conn_total 565882
telemt_me_route_drop_channel_closed_total 158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1195754
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7632
telemt_desync_full_logged_total 2253
telemt_desync_suppressed_total 5379
telemt_desync_frames_bucket_total{bucket="1_2"} 2045
telemt_desync_frames_bucket_total{bucket="3_10"} 2894
telemt_desync_frames_bucket_total{bucket="gt_10"} 2693
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 17376
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 16572
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 782
telemt_user_connections_total{user="hello"} 1189966
telemt_user_connections_current{user="hello"} 478
telemt_user_octets_from_client{user="hello"} 22992191879 (21.41 GB)
telemt_user_octets_to_client{user="hello"} 422872875175 (393.83 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 112287.3 (31h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1375001
telemt_connections_bad_total 64211
telemt_handshake_timeouts_total 46806
telemt_upstream_connect_attempt_total 467668
telemt_upstream_connect_success_total 466101
telemt_upstream_connect_fail_total 1567
telemt_upstream_connect_attempts_per_request{bucket="1"} 467668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33084
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43354
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1567
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 123029
telemt_me_reconnect_success_total 17590
telemt_me_reader_eof_total 19748
telemt_me_idle_close_by_peer_total 19735
telemt_me_route_drop_no_conn_total 354389
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 751844
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3491
telemt_desync_full_logged_total 1178
telemt_desync_suppressed_total 2313
telemt_desync_frames_bucket_total{bucket="1_2"} 685
telemt_desync_frames_bucket_total{bucket="3_10"} 1447
telemt_desync_frames_bucket_total{bucket="gt_10"} 1359
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 19155
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 17572
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1565
telemt_user_connections_total{user="hello"} 1194195
telemt_user_connections_current{user="hello"} 607
telemt_user_octets_from_client{user="hello"} 16173870833 (15.06 GB)
telemt_user_octets_to_client{user="hello"} 417074898906 (388.43 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 112063.0 (31h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 822184
telemt_connections_bad_total 55881
telemt_handshake_timeouts_total 24372
telemt_upstream_connect_attempt_total 26248
telemt_upstream_connect_success_total 26096
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 26248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14032
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 41153
telemt_me_reconnect_success_total 20462
telemt_me_reader_eof_total 22273
telemt_me_idle_close_by_peer_total 22266
telemt_me_route_drop_no_conn_total 328777
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 696184
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2198
telemt_desync_full_logged_total 716
telemt_desync_suppressed_total 1482
telemt_desync_frames_bucket_total{bucket="1_2"} 624
telemt_desync_frames_bucket_total{bucket="3_10"} 852
telemt_desync_frames_bucket_total{bucket="gt_10"} 722
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 21383
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 20450
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 921
telemt_user_connections_total{user="hello"} 694304
telemt_user_connections_current{user="hello"} 458
telemt_user_octets_from_client{user="hello"} 41869184080 (38.99 GB)
telemt_user_octets_to_client{user="hello"} 307360984600 (286.25 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 112122.6 (31h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1306578
telemt_connections_bad_total 57159
telemt_handshake_timeouts_total 22054
telemt_upstream_connect_attempt_total 89041
telemt_upstream_connect_success_total 86632
telemt_upstream_connect_fail_total 2409
telemt_upstream_connect_attempts_per_request{bucket="1"} 89041
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13702
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 367
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2409
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 36669
telemt_me_reconnect_success_total 16274
telemt_me_reader_eof_total 17937
telemt_me_idle_close_by_peer_total 17935
telemt_me_route_drop_no_conn_total 538037
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1061749
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3959
telemt_desync_full_logged_total 1312
telemt_desync_suppressed_total 2647
telemt_desync_frames_bucket_total{bucket="1_2"} 968
telemt_desync_frames_bucket_total{bucket="3_10"} 1662
telemt_desync_frames_bucket_total{bucket="gt_10"} 1329
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 17218
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 16263
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 944
telemt_user_connections_total{user="hello"} 1125089
telemt_user_connections_current{user="hello"} 510
telemt_user_octets_from_client{user="hello"} 17644920062 (16.43 GB)
telemt_user_octets_to_client{user="hello"} 530159587962 (493.75 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 112094.5 (31h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 863448
telemt_connections_bad_total 100138
telemt_handshake_timeouts_total 6858
telemt_upstream_connect_attempt_total 45808
telemt_upstream_connect_success_total 45180
telemt_upstream_connect_fail_total 628
telemt_upstream_connect_attempts_per_request{bucket="1"} 45808
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28269
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16498
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 413
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 628
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 58066
telemt_me_reconnect_success_total 23104
telemt_me_reader_eof_total 25056
telemt_me_idle_close_by_peer_total 25053
telemt_me_route_drop_no_conn_total 274587
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 697102
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3213
telemt_desync_full_logged_total 959
telemt_desync_suppressed_total 2254
telemt_desync_frames_bucket_total{bucket="1_2"} 1008
telemt_desync_frames_bucket_total{bucket="3_10"} 1285
telemt_desync_frames_bucket_total{bucket="gt_10"} 920
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24567
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 23096
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1463
telemt_user_connections_total{user="hello"} 713703
telemt_user_connections_current{user="hello"} 451
telemt_user_octets_from_client{user="hello"} 13775057136 (12.83 GB)
telemt_user_octets_to_client{user="hello"} 353722369628 (329.43 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 112255.4 (31h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1110771
telemt_connections_bad_total 115873
telemt_handshake_timeouts_total 9709
telemt_upstream_connect_attempt_total 22324
telemt_upstream_connect_success_total 22196
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 22324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11441
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 27900
telemt_me_reconnect_success_total 16612
telemt_me_reader_eof_total 18016
telemt_me_idle_close_by_peer_total 18014
telemt_me_route_drop_no_conn_total 761345
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1083792
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
telemt_pool_swap_total 99
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 17228
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 16598
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 616
telemt_user_connections_total{user="hello"} 914621
telemt_user_connections_current{user="hello"} 408
telemt_user_octets_from_client{user="hello"} 14842476816 (13.82 GB)
telemt_user_octets_to_client{user="hello"} 395938088788 (368.75 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 60022.7 (16h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 416899
telemt_connections_bad_total 44714
telemt_handshake_timeouts_total 11020
telemt_upstream_connect_attempt_total 22285
telemt_upstream_connect_success_total 22076
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 22285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10145
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 30538
telemt_me_reconnect_success_total 18931
telemt_me_reader_eof_total 20021
telemt_me_idle_close_by_peer_total 20021
telemt_me_seq_mismatch_total 26
telemt_me_route_drop_no_conn_total 103182
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 302166
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 30
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1291
telemt_desync_full_logged_total 401
telemt_desync_suppressed_total 890
telemt_desync_frames_bucket_total{bucket="1_2"} 223
telemt_desync_frames_bucket_total{bucket="3_10"} 576
telemt_desync_frames_bucket_total{bucket="gt_10"} 492
telemt_pool_swap_total 39
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19505
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 18895
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 574
telemt_user_connections_total{user="hello"} 302102
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 22508637881 (20.96 GB)
telemt_user_octets_to_client{user="hello"} 255698299814 (238.14 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 28
```