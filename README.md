# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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

# Server Metrics 2026-03-19 20:53:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 12957.2 (3h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 345156
telemt_connections_bad_total 16666
telemt_connections_current 922
telemt_connections_me_current 922
telemt_handshake_timeouts_total 5225
telemt_upstream_connect_attempt_total 2053
telemt_upstream_connect_success_total 2031
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 2053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1040
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 1361
telemt_me_reconnect_success_total 1352
telemt_me_reader_eof_total 1424
telemt_me_idle_close_by_peer_total 1424
telemt_me_route_drop_no_conn_total 105455
telemt_me_route_drop_channel_closed_total 47
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 272313
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1381
telemt_desync_full_logged_total 472
telemt_desync_suppressed_total 909
telemt_desync_frames_bucket_total{bucket="1_2"} 290
telemt_desync_frames_bucket_total{bucket="3_10"} 401
telemt_desync_frames_bucket_total{bucket="gt_10"} 690
telemt_pool_swap_total 14
telemt_me_writer_close_signal_drop_total 31
telemt_me_writer_removed_unexpected_total 1385
telemt_me_writer_restored_same_endpoint_total 1339
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 272563
telemt_user_connections_current{user="hello"} 922
telemt_user_octets_from_client{user="hello"} 10689618444 (9.96 GB)
telemt_user_octets_to_client{user="hello"} 99348144132 (92.53 GB)
telemt_user_unique_ips_current{user="hello"} 345
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 29410.4 (8h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2590303
telemt_connections_bad_total 109686
telemt_connections_current 2571
telemt_connections_me_current 2571
telemt_handshake_timeouts_total 50199
telemt_upstream_connect_attempt_total 6068
telemt_upstream_connect_success_total 5974
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 6068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3755
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2174
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 7488
telemt_me_reconnect_success_total 3260
telemt_me_reader_eof_total 3515
telemt_me_idle_close_by_peer_total 3515
telemt_me_route_drop_no_conn_total 1377820
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2204185
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9636
telemt_desync_full_logged_total 3159
telemt_desync_suppressed_total 6477
telemt_desync_frames_bucket_total{bucket="1_2"} 1776
telemt_desync_frames_bucket_total{bucket="3_10"} 3780
telemt_desync_frames_bucket_total{bucket="gt_10"} 4080
telemt_pool_swap_total 22
telemt_me_writer_close_signal_drop_total 38
telemt_me_writer_removed_unexpected_total 3425
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 3205
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 2204136
telemt_user_connections_current{user="hello"} 2571
telemt_user_octets_from_client{user="hello"} 33996992942 (31.66 GB)
telemt_user_octets_to_client{user="hello"} 778720813602 (725.24 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 960
telemt_user_unique_ips_recent_window{user="hello"} 291
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 29388.7 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2485546
telemt_connections_bad_total 400464
telemt_connections_current 1966
telemt_connections_me_current 1966
telemt_handshake_timeouts_total 29109
telemt_upstream_connect_attempt_total 4554
telemt_upstream_connect_success_total 4521
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 4554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2146
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3955
telemt_me_reconnect_success_total 3033
telemt_me_reader_eof_total 3142
telemt_me_idle_close_by_peer_total 3141
telemt_me_route_drop_no_conn_total 1820377
telemt_me_route_drop_channel_closed_total 163
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1780628
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6678
telemt_desync_full_logged_total 2001
telemt_desync_suppressed_total 4677
telemt_desync_frames_bucket_total{bucket="1_2"} 1709
telemt_desync_frames_bucket_total{bucket="3_10"} 2512
telemt_desync_frames_bucket_total{bucket="gt_10"} 2457
telemt_pool_swap_total 26
telemt_me_writer_close_signal_drop_total 57
telemt_me_writer_removed_unexpected_total 3046
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3032
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 1776571
telemt_user_connections_current{user="hello"} 1966
telemt_user_octets_from_client{user="hello"} 25327062620 (23.59 GB)
telemt_user_octets_to_client{user="hello"} 625745467612 (582.77 GB)
telemt_user_unique_ips_current{user="hello"} 716
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 29376.3 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2218675
telemt_connections_bad_total 90597
telemt_connections_current 2009
telemt_connections_me_current 2009
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 27688
telemt_upstream_connect_attempt_total 31841
telemt_upstream_connect_success_total 30286
telemt_upstream_connect_fail_total 1555
telemt_upstream_connect_attempts_per_request{bucket="1"} 31841
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24900
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4946
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 421
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1555
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 6044
telemt_me_reconnect_success_total 3500
telemt_me_reader_eof_total 3639
telemt_me_idle_close_by_peer_total 3638
telemt_me_route_drop_no_conn_total 1780439
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1893121
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7575
telemt_desync_full_logged_total 2355
telemt_desync_suppressed_total 5220
telemt_desync_frames_bucket_total{bucket="1_2"} 1886
telemt_desync_frames_bucket_total{bucket="3_10"} 2737
telemt_desync_frames_bucket_total{bucket="gt_10"} 2952
telemt_pool_swap_total 16
telemt_me_writer_close_signal_drop_total 292
telemt_me_writer_removed_unexpected_total 3966
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 3496
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 466
telemt_user_connections_total{user="hello"} 1917309
telemt_user_connections_current{user="hello"} 2009
telemt_user_octets_from_client{user="hello"} 31733376568 (29.55 GB)
telemt_user_octets_to_client{user="hello"} 466898324078 (434.83 GB)
telemt_user_msgs_from_client{user="hello"} 63004
telemt_user_msgs_to_client{user="hello"} 130023
telemt_user_unique_ips_current{user="hello"} 705
telemt_user_unique_ips_recent_window{user="hello"} 214
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 83099.5 (23h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5890910
telemt_connections_bad_total 1029494
telemt_connections_current 2415
telemt_connections_me_current 2415
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 107398
telemt_upstream_connect_attempt_total 66159
telemt_upstream_connect_success_total 63658
telemt_upstream_connect_fail_total 2501
telemt_upstream_connect_attempts_per_request{bucket="1"} 66159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9035
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1056
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2501
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 75731
telemt_me_reconnect_success_total 10315
telemt_me_reader_eof_total 10890
telemt_me_idle_close_by_peer_total 10887
telemt_me_route_drop_no_conn_total 2696036
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4158725
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18249
telemt_desync_full_logged_total 5663
telemt_desync_suppressed_total 12586
telemt_desync_frames_bucket_total{bucket="1_2"} 3128
telemt_desync_frames_bucket_total{bucket="3_10"} 7559
telemt_desync_frames_bucket_total{bucket="gt_10"} 7562
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 10575
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 10291
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 260
telemt_user_connections_total{user="hello"} 4206783
telemt_user_connections_current{user="hello"} 2415
telemt_user_octets_from_client{user="hello"} 65563180403 (61.06 GB)
telemt_user_octets_to_client{user="hello"} 1606925892176 (1.46 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 852
telemt_user_unique_ips_recent_window{user="hello"} 275
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 29339.5 (8h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 595956
telemt_connections_bad_total 46223
telemt_connections_current 527
telemt_connections_me_current 527
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 11492
telemt_upstream_connect_attempt_total 8495
telemt_upstream_connect_success_total 8298
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 8495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4763
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 553
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 3880
telemt_me_reconnect_success_total 3817
telemt_me_reader_eof_total 3961
telemt_me_idle_close_by_peer_total 3960
telemt_me_route_drop_no_conn_total 392635
telemt_me_route_drop_channel_closed_total 141
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 474650
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7065
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_writer_pick_blocking_fallback_total 8012
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1253
telemt_desync_full_logged_total 430
telemt_desync_suppressed_total 823
telemt_desync_frames_bucket_total{bucket="1_2"} 198
telemt_desync_frames_bucket_total{bucket="3_10"} 509
telemt_desync_frames_bucket_total{bucket="gt_10"} 546
telemt_pool_swap_total 22
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 138
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 3851
telemt_me_writer_restored_same_endpoint_total 3808
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 493289
telemt_user_connections_current{user="hello"} 527
telemt_user_octets_from_client{user="hello"} 5545313280 (5.16 GB)
telemt_user_octets_to_client{user="hello"} 106750765102 (99.42 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 29341.0 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1747909
telemt_connections_bad_total 103218
telemt_connections_current 2119
telemt_connections_me_current 2119
telemt_handshake_timeouts_total 30198
telemt_upstream_connect_attempt_total 4889
telemt_upstream_connect_success_total 4852
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 4889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2199
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 3386
telemt_me_reconnect_success_total 3353
telemt_me_reader_eof_total 3524
telemt_me_idle_close_by_peer_total 3524
telemt_me_route_drop_no_conn_total 658783
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1518883
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8084
telemt_desync_full_logged_total 2508
telemt_desync_suppressed_total 5576
telemt_desync_frames_bucket_total{bucket="1_2"} 1509
telemt_desync_frames_bucket_total{bucket="3_10"} 2825
telemt_desync_frames_bucket_total{bucket="gt_10"} 3750
telemt_pool_swap_total 27
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 3415
telemt_me_writer_restored_same_endpoint_total 3336
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 1518039
telemt_user_connections_current{user="hello"} 2119
telemt_user_octets_from_client{user="hello"} 25808642380 (24.04 GB)
telemt_user_octets_to_client{user="hello"} 736585666956 (686.00 GB)
telemt_user_unique_ips_current{user="hello"} 735
telemt_user_unique_ips_recent_window{user="hello"} 212
```