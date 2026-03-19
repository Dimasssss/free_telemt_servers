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

# Server Metrics 2026-03-19 08:00:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 36746.0 (10h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 667117
telemt_connections_bad_total 69265
telemt_connections_current 1541
telemt_connections_me_current 1541
telemt_handshake_timeouts_total 24759
telemt_upstream_connect_attempt_total 6971
telemt_upstream_connect_success_total 6844
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 6971
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3525
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 6166
telemt_me_reconnect_success_total 5016
telemt_me_reader_eof_total 5327
telemt_me_idle_close_by_peer_total 5326
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 189427
telemt_me_route_drop_channel_closed_total 65
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 506830
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3369
telemt_desync_full_logged_total 958
telemt_desync_suppressed_total 2411
telemt_desync_frames_bucket_total{bucket="1_2"} 1190
telemt_desync_frames_bucket_total{bucket="3_10"} 1260
telemt_desync_frames_bucket_total{bucket="gt_10"} 919
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 5110
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 4999
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 503894
telemt_user_connections_current{user="hello"} 1541
telemt_user_octets_from_client{user="hello"} 6720687096 (6.26 GB)
telemt_user_octets_to_client{user="hello"} 167445489920 (155.95 GB)
telemt_user_unique_ips_current{user="hello"} 526
telemt_user_unique_ips_recent_window{user="hello"} 300
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 36750.1 (10h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1600824
telemt_connections_bad_total 92478
telemt_connections_current 4289
telemt_connections_me_current 4289
telemt_handshake_timeouts_total 38306
telemt_upstream_connect_attempt_total 6944
telemt_upstream_connect_success_total 6814
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 6944
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3421
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 6126
telemt_me_reconnect_success_total 4971
telemt_me_reader_eof_total 5262
telemt_me_idle_close_by_peer_total 5262
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 674908
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1317261
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5962
telemt_desync_full_logged_total 1992
telemt_desync_suppressed_total 3970
telemt_desync_frames_bucket_total{bucket="1_2"} 1054
telemt_desync_frames_bucket_total{bucket="3_10"} 2268
telemt_desync_frames_bucket_total{bucket="gt_10"} 2640
telemt_pool_swap_total 29
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 5097
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 4950
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 1317069
telemt_user_connections_current{user="hello"} 4289
telemt_user_octets_from_client{user="hello"} 23385003300 (21.78 GB)
telemt_user_octets_to_client{user="hello"} 513696936812 (478.42 GB)
telemt_user_unique_ips_current{user="hello"} 1471
telemt_user_unique_ips_recent_window{user="hello"} 831
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 36747.4 (10h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1356748
telemt_connections_bad_total 186810
telemt_connections_current 3313
telemt_connections_me_current 3313
telemt_handshake_timeouts_total 35750
telemt_upstream_connect_attempt_total 6524
telemt_upstream_connect_success_total 6524
telemt_upstream_connect_attempts_per_request{bucket="1"} 6524
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3143
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 4711
telemt_me_reconnect_success_total 4686
telemt_me_reader_eof_total 4967
telemt_me_idle_close_by_peer_total 4967
telemt_me_route_drop_no_conn_total 569213
telemt_me_route_drop_channel_closed_total 47
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1027152
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4891
telemt_desync_full_logged_total 1500
telemt_desync_suppressed_total 3391
telemt_desync_frames_bucket_total{bucket="1_2"} 1043
telemt_desync_frames_bucket_total{bucket="3_10"} 1761
telemt_desync_frames_bucket_total{bucket="gt_10"} 2087
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 4774
telemt_me_writer_restored_same_endpoint_total 4670
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 1026742
telemt_user_connections_current{user="hello"} 3313
telemt_user_octets_from_client{user="hello"} 17976674832 (16.74 GB)
telemt_user_octets_to_client{user="hello"} 519250553488 (483.59 GB)
telemt_user_unique_ips_current{user="hello"} 1108
telemt_user_unique_ips_recent_window{user="hello"} 641
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 36800.5 (10h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1388549
telemt_connections_bad_total 91854
telemt_connections_current 3169
telemt_connections_me_current 3169
telemt_handshake_timeouts_total 34484
telemt_upstream_connect_attempt_total 6535
telemt_upstream_connect_success_total 6535
telemt_upstream_connect_attempts_per_request{bucket="1"} 6535
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3304
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3215
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5743
telemt_me_reconnect_success_total 4679
telemt_me_reader_eof_total 4956
telemt_me_idle_close_by_peer_total 4955
telemt_me_route_drop_no_conn_total 530852
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 968710
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3652
telemt_desync_full_logged_total 1256
telemt_desync_suppressed_total 2396
telemt_desync_frames_bucket_total{bucket="1_2"} 714
telemt_desync_frames_bucket_total{bucket="3_10"} 1435
telemt_desync_frames_bucket_total{bucket="gt_10"} 1503
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 4778
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 4655
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 967473
telemt_user_connections_current{user="hello"} 3169
telemt_user_octets_from_client{user="hello"} 13400322176 (12.48 GB)
telemt_user_octets_to_client{user="hello"} 333365693992 (310.47 GB)
telemt_user_unique_ips_current{user="hello"} 1051
telemt_user_unique_ips_recent_window{user="hello"} 681
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 36743.7 (10h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1682987
telemt_connections_bad_total 442315
telemt_connections_current 3671
telemt_connections_me_current 3671
telemt_handshake_timeouts_total 35720
telemt_upstream_connect_attempt_total 6367
telemt_upstream_connect_success_total 6326
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 6367
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3200
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3105
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_reconnect_attempts_total 4525
telemt_me_reconnect_success_total 4492
telemt_me_reader_eof_total 4763
telemt_me_idle_close_by_peer_total 4763
telemt_me_route_drop_no_conn_total 425992
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1028058
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4977
telemt_desync_full_logged_total 1544
telemt_desync_suppressed_total 3433
telemt_desync_frames_bucket_total{bucket="1_2"} 1057
telemt_desync_frames_bucket_total{bucket="3_10"} 2249
telemt_desync_frames_bucket_total{bucket="gt_10"} 1671
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 4552
telemt_me_writer_restored_same_endpoint_total 4468
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 1027716
telemt_user_connections_current{user="hello"} 3671
telemt_user_octets_from_client{user="hello"} 21213091432 (19.76 GB)
telemt_user_octets_to_client{user="hello"} 491736044212 (457.96 GB)
telemt_user_unique_ips_current{user="hello"} 1202
telemt_user_unique_ips_recent_window{user="hello"} 675
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 36756.2 (10h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 286480
telemt_connections_bad_total 14617
telemt_connections_current 883
telemt_connections_me_current 883
telemt_handshake_timeouts_total 2705
telemt_upstream_connect_attempt_total 9509
telemt_upstream_connect_success_total 9263
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 9509
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4711
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 12802
telemt_me_reconnect_success_total 7426
telemt_me_reader_eof_total 7887
telemt_me_idle_close_by_peer_total 7887
telemt_me_route_drop_no_conn_total 133021
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 254531
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 378
telemt_desync_full_logged_total 127
telemt_desync_suppressed_total 251
telemt_desync_frames_bucket_total{bucket="1_2"} 112
telemt_desync_frames_bucket_total{bucket="3_10"} 157
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 7643
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 7396
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 217
telemt_user_connections_total{user="hello"} 254495
telemt_user_connections_current{user="hello"} 883
telemt_user_octets_from_client{user="hello"} 3791231412 (3.53 GB)
telemt_user_octets_to_client{user="hello"} 119807270084 (111.58 GB)
telemt_user_unique_ips_current{user="hello"} 305
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 36746.0 (10h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1078040
telemt_connections_bad_total 95709
telemt_connections_current 3117
telemt_connections_me_current 3117
telemt_handshake_timeouts_total 48642
telemt_upstream_connect_attempt_total 7384
telemt_upstream_connect_success_total 7384
telemt_upstream_connect_attempts_per_request{bucket="1"} 7384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3450
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 6885
telemt_me_reconnect_success_total 5548
telemt_me_reader_eof_total 5890
telemt_me_idle_close_by_peer_total 5890
telemt_me_route_drop_no_conn_total 427106
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 892585
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5331
telemt_desync_full_logged_total 1769
telemt_desync_suppressed_total 3562
telemt_desync_frames_bucket_total{bucket="1_2"} 1043
telemt_desync_frames_bucket_total{bucket="3_10"} 2035
telemt_desync_frames_bucket_total{bucket="gt_10"} 2253
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 5651
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 5533
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 891591
telemt_user_connections_current{user="hello"} 3117
telemt_user_octets_from_client{user="hello"} 13000084676 (12.11 GB)
telemt_user_octets_to_client{user="hello"} 473954225976 (441.40 GB)
telemt_user_unique_ips_current{user="hello"} 978
telemt_user_unique_ips_recent_window{user="hello"} 571
```