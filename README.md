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

# Server Metrics 2026-03-20 03:56:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 38359.5 (10h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 705968
telemt_connections_bad_total 49442
telemt_connections_current 1016
telemt_connections_me_current 1016
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 15425
telemt_upstream_connect_attempt_total 7753
telemt_upstream_connect_success_total 7659
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 7753
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3335
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 4672
telemt_me_reconnect_success_total 4632
telemt_me_reader_eof_total 4901
telemt_me_idle_close_by_peer_total 4900
telemt_me_route_drop_no_conn_total 199750
telemt_me_route_drop_channel_closed_total 64
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 560116
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2736
telemt_desync_full_logged_total 999
telemt_desync_suppressed_total 1737
telemt_desync_frames_bucket_total{bucket="1_2"} 543
telemt_desync_frames_bucket_total{bucket="3_10"} 1025
telemt_desync_frames_bucket_total{bucket="gt_10"} 1168
telemt_pool_swap_total 42
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 4674
telemt_me_writer_restored_same_endpoint_total 4619
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 561473
telemt_user_connections_current{user="hello"} 1016
telemt_user_octets_from_client{user="hello"} 31438836804 (29.28 GB)
telemt_user_octets_to_client{user="hello"} 192559538285 (179.34 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 394
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 54815.0 (15h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3312464
telemt_connections_bad_total 218445
telemt_connections_current 2277
telemt_connections_me_current 2277
telemt_handshake_timeouts_total 71409
telemt_upstream_connect_attempt_total 10562
telemt_upstream_connect_success_total 10374
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 10562
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5910
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4404
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10684
telemt_me_reconnect_success_total 6435
telemt_me_reader_eof_total 6885
telemt_me_idle_close_by_peer_total 6885
telemt_me_route_drop_no_conn_total 1565558
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2778304
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11701
telemt_desync_full_logged_total 3875
telemt_desync_suppressed_total 7826
telemt_desync_frames_bucket_total{bucket="1_2"} 2248
telemt_desync_frames_bucket_total{bucket="3_10"} 4563
telemt_desync_frames_bucket_total{bucket="gt_10"} 4890
telemt_pool_swap_total 48
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 53
telemt_me_writer_removed_unexpected_total 6645
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6380
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 2778013
telemt_user_connections_current{user="hello"} 2277
telemt_user_octets_from_client{user="hello"} 42476746202 (39.56 GB)
telemt_user_octets_to_client{user="hello"} 1043275857358 (971.63 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 939
telemt_user_unique_ips_recent_window{user="hello"} 268
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 54793.2 (15h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3133112
telemt_connections_bad_total 483200
telemt_connections_current 1900
telemt_connections_me_current 1900
telemt_handshake_timeouts_total 50006
telemt_upstream_connect_attempt_total 8942
telemt_upstream_connect_success_total 8877
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 8942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4494
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4366
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7104
telemt_me_reconnect_success_total 6167
telemt_me_reader_eof_total 6486
telemt_me_idle_close_by_peer_total 6485
telemt_me_route_drop_no_conn_total 1980290
telemt_me_route_drop_channel_closed_total 176
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2178412
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8049
telemt_desync_full_logged_total 2472
telemt_desync_suppressed_total 5577
telemt_desync_frames_bucket_total{bucket="1_2"} 1980
telemt_desync_frames_bucket_total{bucket="3_10"} 3054
telemt_desync_frames_bucket_total{bucket="gt_10"} 3015
telemt_pool_swap_total 54
telemt_me_writer_close_signal_drop_total 73
telemt_me_writer_removed_unexpected_total 6229
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 6166
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 2173437
telemt_user_connections_current{user="hello"} 1900
telemt_user_octets_from_client{user="hello"} 32994435848 (30.73 GB)
telemt_user_octets_to_client{user="hello"} 853703430540 (795.07 GB)
telemt_user_unique_ips_current{user="hello"} 713
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 54781.2 (15h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2827029
telemt_connections_bad_total 219380
telemt_connections_current 1755
telemt_connections_me_current 1755
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 33889
telemt_upstream_connect_attempt_total 61452
telemt_upstream_connect_success_total 56954
telemt_upstream_connect_fail_total 4498
telemt_upstream_connect_attempts_per_request{bucket="1"} 61452
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48056
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8323
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 550
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4498
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 9428
telemt_me_reconnect_success_total 6511
telemt_me_reader_eof_total 6786
telemt_me_idle_close_by_peer_total 6785
telemt_me_route_drop_no_conn_total 1934873
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2283953
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8816
telemt_desync_full_logged_total 2817
telemt_desync_suppressed_total 5999
telemt_desync_frames_bucket_total{bucket="1_2"} 2153
telemt_desync_frames_bucket_total{bucket="3_10"} 3223
telemt_desync_frames_bucket_total{bucket="gt_10"} 3440
telemt_pool_swap_total 41
telemt_me_writer_close_signal_drop_total 540
telemt_me_writer_removed_unexpected_total 7187
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 6507
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 676
telemt_user_connections_total{user="hello"} 2330092
telemt_user_connections_current{user="hello"} 1755
telemt_user_octets_from_client{user="hello"} 37152908570 (34.60 GB)
telemt_user_octets_to_client{user="hello"} 683086608327 (636.17 GB)
telemt_user_msgs_from_client{user="hello"} 251914
telemt_user_msgs_to_client{user="hello"} 1773933
telemt_user_unique_ips_current{user="hello"} 640
telemt_user_unique_ips_recent_window{user="hello"} 206
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 108504.3 (30h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6547613
telemt_connections_bad_total 1145827
telemt_connections_current 1889
telemt_connections_me_current 1889
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 117037
telemt_upstream_connect_attempt_total 128929
telemt_upstream_connect_success_total 95637
telemt_upstream_connect_fail_total 33292
telemt_upstream_connect_attempts_per_request{bucket="1"} 128929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81028
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13172
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33292
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 79594
telemt_me_reconnect_success_total 13919
telemt_me_reader_eof_total 14977
telemt_me_idle_close_by_peer_total 14963
telemt_me_route_drop_no_conn_total 2852054
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4607104
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
telemt_desync_total 20042
telemt_desync_full_logged_total 6374
telemt_desync_suppressed_total 13668
telemt_desync_frames_bucket_total{bucket="1_2"} 3542
telemt_desync_frames_bucket_total{bucket="3_10"} 8283
telemt_desync_frames_bucket_total{bucket="gt_10"} 8217
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 14237
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 13894
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 318
telemt_user_connections_total{user="hello"} 4682175
telemt_user_connections_current{user="hello"} 1889
telemt_user_octets_from_client{user="hello"} 74353793220 (69.25 GB)
telemt_user_octets_to_client{user="hello"} 1824514511720 (1.66 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 736
telemt_user_unique_ips_recent_window{user="hello"} 242
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 54744.1 (15h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1185920
telemt_connections_bad_total 94531
telemt_connections_current 754
telemt_connections_me_current 754
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13594
telemt_upstream_connect_attempt_total 13769
telemt_upstream_connect_success_total 13439
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 58
telemt_me_keepalive_timeout_total 546
telemt_me_reconnect_attempts_total 6736
telemt_me_reconnect_success_total 6627
telemt_me_reader_eof_total 7008
telemt_me_idle_close_by_peer_total 7005
telemt_me_route_drop_no_conn_total 473138
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
telemt_desync_total 1422
telemt_desync_full_logged_total 544
telemt_desync_suppressed_total 878
telemt_desync_frames_bucket_total{bucket="1_2"} 220
telemt_desync_frames_bucket_total{bucket="3_10"} 599
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
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
telemt_user_connections_total{user="hello"} 1022604
telemt_user_connections_current{user="hello"} 754
telemt_user_octets_from_client{user="hello"} 8072628203 (7.52 GB)
telemt_user_octets_to_client{user="hello"} 146605694702 (136.54 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 54745.5 (15h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2189550
telemt_connections_bad_total 132826
telemt_connections_current 1950
telemt_connections_me_current 1950
telemt_handshake_timeouts_total 41580
telemt_upstream_connect_attempt_total 9869
telemt_upstream_connect_success_total 9804
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 9869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4476
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7130
telemt_me_reconnect_success_total 7083
telemt_me_reader_eof_total 7478
telemt_me_idle_close_by_peer_total 7478
telemt_me_route_drop_no_conn_total 783771
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1860828
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9589
telemt_desync_full_logged_total 3086
telemt_desync_suppressed_total 6503
telemt_desync_frames_bucket_total{bucket="1_2"} 1860
telemt_desync_frames_bucket_total{bucket="3_10"} 3365
telemt_desync_frames_bucket_total{bucket="gt_10"} 4364
telemt_pool_swap_total 55
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 7181
telemt_me_writer_restored_same_endpoint_total 7066
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 1859929
telemt_user_connections_current{user="hello"} 1950
telemt_user_octets_from_client{user="hello"} 35556070700 (33.11 GB)
telemt_user_octets_to_client{user="hello"} 962856066836 (896.73 GB)
telemt_user_unique_ips_current{user="hello"} 686
telemt_user_unique_ips_recent_window{user="hello"} 198
```