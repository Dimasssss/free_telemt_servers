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

# Server Metrics 2026-03-14 08:03:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 174628.8 (48h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 670621
telemt_connections_bad_total 32434
telemt_handshake_timeouts_total 13178
telemt_upstream_connect_attempt_total 44351
telemt_upstream_connect_success_total 44128
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 44351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20189
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23787
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5702
telemt_me_reconnect_attempts_total 39757
telemt_me_reconnect_success_total 35062
telemt_me_reader_eof_total 37493
telemt_me_idle_close_by_peer_total 37492
telemt_me_route_drop_no_conn_total 221921
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 571718
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2215
telemt_desync_full_logged_total 751
telemt_desync_suppressed_total 1464
telemt_desync_frames_bucket_total{bucket="1_2"} 478
telemt_desync_frames_bucket_total{bucket="3_10"} 814
telemt_desync_frames_bucket_total{bucket="gt_10"} 923
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 35583
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 35042
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 521
telemt_user_connections_total{user="hello"} 571601
telemt_user_connections_current{user="hello"} 325
telemt_user_octets_from_client{user="hello"} 16625594602 (15.48 GB)
telemt_user_octets_to_client{user="hello"} 273937671540 (255.12 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 174522.2 (48h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 337492
telemt_connections_bad_total 2328
telemt_handshake_timeouts_total 2690
telemt_upstream_connect_attempt_total 151516
telemt_upstream_connect_success_total 150228
telemt_upstream_connect_fail_total 1288
telemt_upstream_connect_attempts_per_request{bucket="1"} 151516
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 110349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37451
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2428
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1288
telemt_me_keepalive_timeout_total 4038
telemt_me_reconnect_attempts_total 178840
telemt_me_reconnect_success_total 38244
telemt_me_reader_eof_total 43685
telemt_me_idle_close_by_peer_total 43685
telemt_me_route_drop_no_conn_total 112719
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 216225
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 43
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
telemt_me_writer_removed_unexpected_total 43001
telemt_me_refill_failed_total 4387
telemt_me_writer_restored_same_endpoint_total 38227
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4757
telemt_user_connections_total{user="hello"} 319331
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 3302488963 (3.08 GB)
telemt_user_octets_to_client{user="hello"} 103981145087 (96.84 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 174486.4 (48h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 394756
telemt_connections_bad_total 3181
telemt_handshake_timeouts_total 35311
telemt_upstream_connect_attempt_total 46021
telemt_upstream_connect_success_total 46012
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 46021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24906
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3504
telemt_me_reconnect_attempts_total 38583
telemt_me_reconnect_success_total 37296
telemt_me_reader_eof_total 40103
telemt_me_idle_close_by_peer_total 40103
telemt_me_route_drop_no_conn_total 142726
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 342440
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
telemt_pool_swap_total 165
telemt_me_writer_removed_unexpected_total 37747
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 37275
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 451
telemt_user_connections_total{user="hello"} 342203
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 13614653060 (12.68 GB)
telemt_user_octets_to_client{user="hello"} 141310141512 (131.61 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 174461.5 (48h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 496936
telemt_connections_bad_total 16275
telemt_handshake_timeouts_total 4552
telemt_upstream_connect_attempt_total 76564
telemt_upstream_connect_success_total 65952
telemt_upstream_connect_fail_total 10612
telemt_upstream_connect_attempts_per_request{bucket="1"} 76564
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26846
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 343
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10612
telemt_me_keepalive_timeout_total 5455
telemt_me_reconnect_attempts_total 145363
telemt_me_reconnect_success_total 38244
telemt_me_reader_eof_total 42820
telemt_me_idle_close_by_peer_total 42812
telemt_me_route_drop_no_conn_total 180008
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 423833
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1827
telemt_desync_full_logged_total 544
telemt_desync_suppressed_total 1283
telemt_desync_frames_bucket_total{bucket="1_2"} 431
telemt_desync_frames_bucket_total{bucket="3_10"} 696
telemt_desync_frames_bucket_total{bucket="gt_10"} 700
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 42029
telemt_me_refill_failed_total 3340
telemt_me_writer_restored_same_endpoint_total 38234
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3785
telemt_user_connections_total{user="hello"} 442709
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 9512573891 (8.86 GB)
telemt_user_octets_to_client{user="hello"} 181290342368 (168.84 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 124633.1 (34h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203870
telemt_connections_bad_total 30605
telemt_handshake_timeouts_total 1764
telemt_upstream_connect_attempt_total 43733
telemt_upstream_connect_success_total 43313
telemt_upstream_connect_fail_total 420
telemt_upstream_connect_attempts_per_request{bucket="1"} 43733
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21497
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 420
telemt_me_keepalive_timeout_total 2532
telemt_me_reconnect_attempts_total 45658
telemt_me_reconnect_success_total 32222
telemt_me_reader_eof_total 34487
telemt_me_idle_close_by_peer_total 34487
telemt_me_route_drop_no_conn_total 61021
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161023
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 701
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 335
telemt_desync_frames_bucket_total{bucket="gt_10"} 252
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 32940
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 32204
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 718
telemt_user_connections_total{user="hello"} 165783
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 2453260049 (2.28 GB)
telemt_user_octets_to_client{user="hello"} 78752627947 (73.34 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 174417.5 (48h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1001250
telemt_connections_bad_total 36240
telemt_handshake_timeouts_total 26204
telemt_upstream_connect_attempt_total 36134
telemt_upstream_connect_success_total 35943
telemt_upstream_connect_fail_total 191
telemt_upstream_connect_attempts_per_request{bucket="1"} 36134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18999
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 191
telemt_me_keepalive_timeout_total 4729
telemt_me_reconnect_attempts_total 32010
telemt_me_reconnect_success_total 27328
telemt_me_reader_eof_total 29335
telemt_me_idle_close_by_peer_total 29332
telemt_me_route_drop_no_conn_total 470840
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 927895
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 770
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 516
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 253
telemt_desync_frames_bucket_total{bucket="gt_10"} 260
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 27821
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 27321
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 493
telemt_user_connections_total{user="hello"} 900533
telemt_user_connections_current{user="hello"} 389
telemt_user_octets_from_client{user="hello"} 15350194784 (14.30 GB)
telemt_user_octets_to_client{user="hello"} 450135084980 (419.22 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 71
```