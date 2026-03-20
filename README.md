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

# Server Metrics 2026-03-20 05:59:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 45692.8 (12h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 892439
telemt_connections_bad_total 57043
telemt_connections_current 1294
telemt_connections_me_current 1294
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 22717
telemt_upstream_connect_attempt_total 8872
telemt_upstream_connect_success_total 8771
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 8872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4850
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3891
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 5440
telemt_me_reconnect_success_total 5396
telemt_me_reader_eof_total 5719
telemt_me_idle_close_by_peer_total 5718
telemt_me_route_drop_no_conn_total 248821
telemt_me_route_drop_channel_closed_total 87
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 719716
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3824
telemt_desync_full_logged_total 1381
telemt_desync_suppressed_total 2443
telemt_desync_frames_bucket_total{bucket="1_2"} 727
telemt_desync_frames_bucket_total{bucket="3_10"} 1505
telemt_desync_frames_bucket_total{bucket="gt_10"} 1592
telemt_pool_swap_total 50
telemt_me_writer_close_signal_drop_total 48
telemt_me_writer_removed_unexpected_total 5453
telemt_me_writer_restored_same_endpoint_total 5383
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 721273
telemt_user_connections_current{user="hello"} 1294
telemt_user_octets_from_client{user="hello"} 33453872032 (31.16 GB)
telemt_user_octets_to_client{user="hello"} 252116938721 (234.80 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 527
telemt_user_unique_ips_recent_window{user="hello"} 196
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 62148.8 (17h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3932646
telemt_connections_bad_total 351495
telemt_connections_current 4153
telemt_connections_me_current 4153
telemt_handshake_timeouts_total 94497
telemt_upstream_connect_attempt_total 11625
telemt_upstream_connect_success_total 11412
telemt_upstream_connect_fail_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 11625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4916
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 213
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 11360
telemt_me_reconnect_success_total 7107
telemt_me_reader_eof_total 7609
telemt_me_idle_close_by_peer_total 7608
telemt_me_route_drop_no_conn_total 1745838
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3221064
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13102
telemt_desync_full_logged_total 4366
telemt_desync_suppressed_total 8736
telemt_desync_frames_bucket_total{bucket="1_2"} 2511
telemt_desync_frames_bucket_total{bucket="3_10"} 5104
telemt_desync_frames_bucket_total{bucket="gt_10"} 5487
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 58
telemt_me_writer_removed_unexpected_total 7330
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7052
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 223
telemt_user_connections_total{user="hello"} 3220776
telemt_user_connections_current{user="hello"} 4153
telemt_user_octets_from_client{user="hello"} 48313731818 (45.00 GB)
telemt_user_octets_to_client{user="hello"} 1224236677810 (1.11 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1506
telemt_user_unique_ips_recent_window{user="hello"} 563
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 62126.9 (17h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3539767
telemt_connections_bad_total 503971
telemt_connections_current 3511
telemt_connections_me_current 3511
telemt_handshake_timeouts_total 54512
telemt_upstream_connect_attempt_total 10000
telemt_upstream_connect_success_total 9930
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 10000
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4859
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7807
telemt_me_reconnect_success_total 6862
telemt_me_reader_eof_total 7235
telemt_me_idle_close_by_peer_total 7234
telemt_me_route_drop_no_conn_total 2088352
telemt_me_route_drop_channel_closed_total 185
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2490981
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9152
telemt_desync_full_logged_total 2848
telemt_desync_suppressed_total 6304
telemt_desync_frames_bucket_total{bucket="1_2"} 2278
telemt_desync_frames_bucket_total{bucket="3_10"} 3488
telemt_desync_frames_bucket_total{bucket="gt_10"} 3386
telemt_pool_swap_total 62
telemt_me_writer_close_signal_drop_total 80
telemt_me_writer_removed_unexpected_total 6939
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 6861
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 2486026
telemt_user_connections_current{user="hello"} 3511
telemt_user_octets_from_client{user="hello"} 37569781972 (34.99 GB)
telemt_user_octets_to_client{user="hello"} 1016114079420 (946.33 GB)
telemt_user_unique_ips_current{user="hello"} 1186
telemt_user_unique_ips_recent_window{user="hello"} 466
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 62114.2 (17h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3379469
telemt_connections_bad_total 248548
telemt_connections_current 3775
telemt_connections_me_current 3775
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 50344
telemt_upstream_connect_attempt_total 67397
telemt_upstream_connect_success_total 62684
telemt_upstream_connect_fail_total 4713
telemt_upstream_connect_attempts_per_request{bucket="1"} 67397
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9563
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 711
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4713
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 10186
telemt_me_reconnect_success_total 7214
telemt_me_reader_eof_total 7521
telemt_me_idle_close_by_peer_total 7520
telemt_me_route_drop_no_conn_total 2511304
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2754838
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10138
telemt_desync_full_logged_total 3181
telemt_desync_suppressed_total 6957
telemt_desync_frames_bucket_total{bucket="1_2"} 2405
telemt_desync_frames_bucket_total{bucket="3_10"} 3790
telemt_desync_frames_bucket_total{bucket="gt_10"} 3943
telemt_pool_swap_total 49
telemt_me_writer_close_signal_drop_total 674
telemt_me_writer_removed_unexpected_total 7928
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7210
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 410
telemt_me_writer_removed_unexpected_minus_restored_total 714
telemt_user_connections_total{user="hello"} 2805324
telemt_user_connections_current{user="hello"} 3775
telemt_user_octets_from_client{user="hello"} 41804427880 (38.93 GB)
telemt_user_octets_to_client{user="hello"} 796735593515 (742.02 GB)
telemt_user_msgs_from_client{user="hello"} 260491
telemt_user_msgs_to_client{user="hello"} 1782062
telemt_user_unique_ips_current{user="hello"} 1176
telemt_user_unique_ips_recent_window{user="hello"} 624
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 115837.8 (32h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6999681
telemt_connections_bad_total 1217216
telemt_connections_current 3727
telemt_connections_me_current 3727
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 122756
telemt_upstream_connect_attempt_total 129969
telemt_upstream_connect_success_total 96665
telemt_upstream_connect_fail_total 33304
telemt_upstream_connect_attempts_per_request{bucket="1"} 129969
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13686
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1439
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33304
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 80276
telemt_me_reconnect_success_total 14595
telemt_me_reader_eof_total 15704
telemt_me_idle_close_by_peer_total 15690
telemt_me_route_drop_no_conn_total 3009720
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4950010
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
telemt_desync_total 21341
telemt_desync_full_logged_total 6806
telemt_desync_suppressed_total 14535
telemt_desync_frames_bucket_total{bucket="1_2"} 3800
telemt_desync_frames_bucket_total{bucket="3_10"} 8836
telemt_desync_frames_bucket_total{bucket="gt_10"} 8705
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 14930
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 14570
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 335
telemt_user_connections_total{user="hello"} 5024738
telemt_user_connections_current{user="hello"} 3727
telemt_user_octets_from_client{user="hello"} 80647380356 (75.11 GB)
telemt_user_octets_to_client{user="hello"} 1997693205404 (1.82 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 1265
telemt_user_unique_ips_recent_window{user="hello"} 507
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 62077.5 (17h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1774123
telemt_connections_bad_total 107592
telemt_connections_current 731
telemt_connections_me_current 731
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 15318
telemt_upstream_connect_attempt_total 13771
telemt_upstream_connect_success_total 13441
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 60
telemt_me_keepalive_timeout_total 560
telemt_me_reconnect_attempts_total 6736
telemt_me_reconnect_success_total 6627
telemt_me_reader_eof_total 7008
telemt_me_idle_close_by_peer_total 7005
telemt_me_route_drop_no_conn_total 473703
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585597
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
telemt_desync_total 1691
telemt_desync_full_logged_total 604
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 273
telemt_desync_frames_bucket_total{bucket="3_10"} 753
telemt_desync_frames_bucket_total{bucket="gt_10"} 665
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 151
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 6689
telemt_me_writer_restored_same_endpoint_total 6618
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 1586433
telemt_user_connections_current{user="hello"} 731
telemt_user_octets_from_client{user="hello"} 9513216655 (8.86 GB)
telemt_user_octets_to_client{user="hello"} 146639389514 (136.57 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 62078.9 (17h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2579461
telemt_connections_bad_total 161355
telemt_connections_current 3508
telemt_connections_me_current 3508
telemt_handshake_timeouts_total 46029
telemt_upstream_connect_attempt_total 11047
telemt_upstream_connect_success_total 10979
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 11047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5022
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7961
telemt_me_reconnect_success_total 7911
telemt_me_reader_eof_total 8360
telemt_me_idle_close_by_peer_total 8360
telemt_me_route_drop_no_conn_total 890376
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2157742
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10774
telemt_desync_full_logged_total 3539
telemt_desync_suppressed_total 7235
telemt_desync_frames_bucket_total{bucket="1_2"} 2097
telemt_desync_frames_bucket_total{bucket="3_10"} 3792
telemt_desync_frames_bucket_total{bucket="gt_10"} 4885
telemt_pool_swap_total 63
telemt_me_writer_close_signal_drop_total 43
telemt_me_writer_removed_unexpected_total 8020
telemt_me_writer_restored_same_endpoint_total 7894
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 2156496
telemt_user_connections_current{user="hello"} 3508
telemt_user_octets_from_client{user="hello"} 47235233596 (43.99 GB)
telemt_user_octets_to_client{user="hello"} 1138489039172 (1.04 TB)
telemt_user_unique_ips_current{user="hello"} 1150
telemt_user_unique_ips_recent_window{user="hello"} 465
```