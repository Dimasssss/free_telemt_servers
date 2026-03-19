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

# Server Metrics 2026-03-19 08:11:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 37359.7 (10h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 689543
telemt_connections_bad_total 71099
telemt_connections_current 1581
telemt_connections_me_current 1581
telemt_handshake_timeouts_total 25214
telemt_upstream_connect_attempt_total 7088
telemt_upstream_connect_success_total 6958
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 7088
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3580
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 6235
telemt_me_reconnect_success_total 5082
telemt_me_reader_eof_total 5397
telemt_me_idle_close_by_peer_total 5396
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 196498
telemt_me_route_drop_channel_closed_total 75
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 525151
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3463
telemt_desync_full_logged_total 992
telemt_desync_suppressed_total 2471
telemt_desync_frames_bucket_total{bucket="1_2"} 1205
telemt_desync_frames_bucket_total{bucket="3_10"} 1295
telemt_desync_frames_bucket_total{bucket="gt_10"} 963
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 5176
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 5065
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 522181
telemt_user_connections_current{user="hello"} 1581
telemt_user_octets_from_client{user="hello"} 7060109508 (6.58 GB)
telemt_user_octets_to_client{user="hello"} 172967193720 (161.09 GB)
telemt_user_unique_ips_current{user="hello"} 542
telemt_user_unique_ips_recent_window{user="hello"} 239
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 37363.8 (10h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1672030
telemt_connections_bad_total 96815
telemt_connections_current 4154
telemt_connections_me_current 4154
telemt_handshake_timeouts_total 39777
telemt_upstream_connect_attempt_total 7094
telemt_upstream_connect_success_total 6961
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 7094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3493
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 6227
telemt_me_reconnect_success_total 5070
telemt_me_reader_eof_total 5376
telemt_me_idle_close_by_peer_total 5376
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 739181
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1376937
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6106
telemt_desync_full_logged_total 2042
telemt_desync_suppressed_total 4064
telemt_desync_frames_bucket_total{bucket="1_2"} 1073
telemt_desync_frames_bucket_total{bucket="3_10"} 2316
telemt_desync_frames_bucket_total{bucket="gt_10"} 2717
telemt_pool_swap_total 30
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 5198
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 5049
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 1376730
telemt_user_connections_current{user="hello"} 4154
telemt_user_octets_from_client{user="hello"} 23968949732 (22.32 GB)
telemt_user_octets_to_client{user="hello"} 530760790636 (494.31 GB)
telemt_user_unique_ips_current{user="hello"} 1391
telemt_user_unique_ips_recent_window{user="hello"} 652
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 37361.1 (10h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1419936
telemt_connections_bad_total 189049
telemt_connections_current 3212
telemt_connections_me_current 3212
telemt_handshake_timeouts_total 36453
telemt_upstream_connect_attempt_total 6669
telemt_upstream_connect_success_total 6669
telemt_upstream_connect_attempts_per_request{bucket="1"} 6669
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3459
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3198
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 4807
telemt_me_reconnect_success_total 4779
telemt_me_reader_eof_total 5063
telemt_me_idle_close_by_peer_total 5063
telemt_me_route_drop_no_conn_total 647108
telemt_me_route_drop_channel_closed_total 48
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1083781
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5103
telemt_desync_full_logged_total 1562
telemt_desync_suppressed_total 3541
telemt_desync_frames_bucket_total{bucket="1_2"} 1099
telemt_desync_frames_bucket_total{bucket="3_10"} 1835
telemt_desync_frames_bucket_total{bucket="gt_10"} 2169
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 4869
telemt_me_writer_restored_same_endpoint_total 4763
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 1083378
telemt_user_connections_current{user="hello"} 3212
telemt_user_octets_from_client{user="hello"} 18463641976 (17.20 GB)
telemt_user_octets_to_client{user="hello"} 541135250696 (503.97 GB)
telemt_user_unique_ips_current{user="hello"} 1080
telemt_user_unique_ips_recent_window{user="hello"} 484
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 37414.4 (10h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1453219
telemt_connections_bad_total 92846
telemt_connections_current 3076
telemt_connections_me_current 3076
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 36302
telemt_upstream_connect_attempt_total 14920
telemt_upstream_connect_success_total 14824
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 14920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10705
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3971
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7167
telemt_me_reconnect_success_total 4779
telemt_me_reader_eof_total 5083
telemt_me_idle_close_by_peer_total 5082
telemt_me_route_drop_no_conn_total 591334
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1017114
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3758
telemt_desync_full_logged_total 1288
telemt_desync_suppressed_total 2470
telemt_desync_frames_bucket_total{bucket="1_2"} 732
telemt_desync_frames_bucket_total{bucket="3_10"} 1477
telemt_desync_frames_bucket_total{bucket="gt_10"} 1549
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 5032
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 4755
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 1023995
telemt_user_connections_current{user="hello"} 3076
telemt_user_octets_from_client{user="hello"} 13787897696 (12.84 GB)
telemt_user_octets_to_client{user="hello"} 342346482322 (318.84 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 912
telemt_user_unique_ips_recent_window{user="hello"} 511
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 37357.7 (10h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1742418
telemt_connections_bad_total 453199
telemt_connections_current 3389
telemt_connections_me_current 3389
telemt_handshake_timeouts_total 36558
telemt_upstream_connect_attempt_total 6478
telemt_upstream_connect_success_total 6434
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 6478
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 4584
telemt_me_reconnect_success_total 4551
telemt_me_reader_eof_total 4826
telemt_me_idle_close_by_peer_total 4826
telemt_me_route_drop_no_conn_total 448154
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1071151
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5206
telemt_desync_full_logged_total 1610
telemt_desync_suppressed_total 3596
telemt_desync_frames_bucket_total{bucket="1_2"} 1078
telemt_desync_frames_bucket_total{bucket="3_10"} 2358
telemt_desync_frames_bucket_total{bucket="gt_10"} 1770
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 4611
telemt_me_writer_restored_same_endpoint_total 4527
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 1070793
telemt_user_connections_current{user="hello"} 3389
telemt_user_octets_from_client{user="hello"} 21760423960 (20.27 GB)
telemt_user_octets_to_client{user="hello"} 508800967616 (473.86 GB)
telemt_user_unique_ips_current{user="hello"} 1164
telemt_user_unique_ips_recent_window{user="hello"} 551
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 37370.3 (10h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 297587
telemt_connections_bad_total 14620
telemt_connections_current 831
telemt_connections_me_current 831
telemt_handshake_timeouts_total 2745
telemt_upstream_connect_attempt_total 9632
telemt_upstream_connect_success_total 9386
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 9632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4771
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 12880
telemt_me_reconnect_success_total 7504
telemt_me_reader_eof_total 7972
telemt_me_idle_close_by_peer_total 7972
telemt_me_route_drop_no_conn_total 137792
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 265257
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 392
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 260
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 164
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 7721
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 7474
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 217
telemt_user_connections_total{user="hello"} 265219
telemt_user_connections_current{user="hello"} 831
telemt_user_octets_from_client{user="hello"} 3918673764 (3.65 GB)
telemt_user_octets_to_client{user="hello"} 122657483664 (114.23 GB)
telemt_user_unique_ips_current{user="hello"} 307
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 37360.0 (10h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1134559
telemt_connections_bad_total 97071
telemt_connections_current 2850
telemt_connections_me_current 2850
telemt_handshake_timeouts_total 50088
telemt_upstream_connect_attempt_total 7553
telemt_upstream_connect_success_total 7552
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3526
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 7005
telemt_me_reconnect_success_total 5665
telemt_me_reader_eof_total 6008
telemt_me_idle_close_by_peer_total 6007
telemt_me_route_drop_no_conn_total 450747
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 944447
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5590
telemt_desync_full_logged_total 1842
telemt_desync_suppressed_total 3748
telemt_desync_frames_bucket_total{bucket="1_2"} 1090
telemt_desync_frames_bucket_total{bucket="3_10"} 2108
telemt_desync_frames_bucket_total{bucket="gt_10"} 2392
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 5770
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 5650
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 943431
telemt_user_connections_current{user="hello"} 2850
telemt_user_octets_from_client{user="hello"} 13400544588 (12.48 GB)
telemt_user_octets_to_client{user="hello"} 488185291928 (454.66 GB)
telemt_user_unique_ips_current{user="hello"} 943
telemt_user_unique_ips_recent_window{user="hello"} 404
```