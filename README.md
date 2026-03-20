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

# Server Metrics 2026-03-20 03:31:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 36831.2 (10h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 679909
telemt_connections_bad_total 48079
telemt_connections_current 895
telemt_connections_me_current 895
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 14989
telemt_upstream_connect_attempt_total 7477
telemt_upstream_connect_success_total 7385
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 7477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3197
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 4486
telemt_me_reconnect_success_total 4446
telemt_me_reader_eof_total 4701
telemt_me_idle_close_by_peer_total 4700
telemt_me_route_drop_no_conn_total 192453
telemt_me_route_drop_channel_closed_total 61
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 537890
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2522
telemt_desync_full_logged_total 925
telemt_desync_suppressed_total 1597
telemt_desync_frames_bucket_total{bucket="1_2"} 517
telemt_desync_frames_bucket_total{bucket="3_10"} 910
telemt_desync_frames_bucket_total{bucket="gt_10"} 1095
telemt_pool_swap_total 40
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 4485
telemt_me_writer_restored_same_endpoint_total 4433
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 539213
telemt_user_connections_current{user="hello"} 895
telemt_user_octets_from_client{user="hello"} 31141665808 (29.00 GB)
telemt_user_octets_to_client{user="hello"} 183419785721 (170.82 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 371
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 53286.8 (14h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3230944
telemt_connections_bad_total 192892
telemt_connections_current 2200
telemt_connections_me_current 2200
telemt_handshake_timeouts_total 69926
telemt_upstream_connect_attempt_total 10380
telemt_upstream_connect_success_total 10196
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 10380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5823
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4313
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10549
telemt_me_reconnect_success_total 6299
telemt_me_reader_eof_total 6742
telemt_me_idle_close_by_peer_total 6742
telemt_me_route_drop_no_conn_total 1548668
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2725865
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11609
telemt_desync_full_logged_total 3835
telemt_desync_suppressed_total 7774
telemt_desync_frames_bucket_total{bucket="1_2"} 2225
telemt_desync_frames_bucket_total{bucket="3_10"} 4528
telemt_desync_frames_bucket_total{bucket="gt_10"} 4856
telemt_pool_swap_total 47
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 53
telemt_me_writer_removed_unexpected_total 6506
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6244
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 207
telemt_user_connections_total{user="hello"} 2725592
telemt_user_connections_current{user="hello"} 2200
telemt_user_octets_from_client{user="hello"} 41436602010 (38.59 GB)
telemt_user_octets_to_client{user="hello"} 1016386643446 (946.58 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 857
telemt_user_unique_ips_recent_window{user="hello"} 265
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 53265.0 (14h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3089867
telemt_connections_bad_total 482317
telemt_connections_current 1715
telemt_connections_me_current 1715
telemt_handshake_timeouts_total 49218
telemt_upstream_connect_attempt_total 8726
telemt_upstream_connect_success_total 8661
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 8726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4264
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6931
telemt_me_reconnect_success_total 5995
telemt_me_reader_eof_total 6303
telemt_me_idle_close_by_peer_total 6302
telemt_me_route_drop_no_conn_total 1968808
telemt_me_route_drop_channel_closed_total 175
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2143985
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7988
telemt_desync_full_logged_total 2448
telemt_desync_suppressed_total 5540
telemt_desync_frames_bucket_total{bucket="1_2"} 1960
telemt_desync_frames_bucket_total{bucket="3_10"} 3033
telemt_desync_frames_bucket_total{bucket="gt_10"} 2995
telemt_pool_swap_total 53
telemt_me_writer_close_signal_drop_total 73
telemt_me_writer_removed_unexpected_total 6055
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5994
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 2139010
telemt_user_connections_current{user="hello"} 1715
telemt_user_octets_from_client{user="hello"} 32615920880 (30.38 GB)
telemt_user_octets_to_client{user="hello"} 834822730772 (777.49 GB)
telemt_user_unique_ips_current{user="hello"} 653
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 53252.8 (14h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2773899
telemt_connections_bad_total 213044
telemt_connections_current 1599
telemt_connections_me_current 1599
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 33075
telemt_upstream_connect_attempt_total 58667
telemt_upstream_connect_success_total 54251
telemt_upstream_connect_fail_total 4416
telemt_upstream_connect_attempts_per_request{bucket="1"} 58667
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8158
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 548
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4416
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 9260
telemt_me_reconnect_success_total 6351
telemt_me_reader_eof_total 6616
telemt_me_idle_close_by_peer_total 6615
telemt_me_route_drop_no_conn_total 1923463
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2244229
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8679
telemt_desync_full_logged_total 2770
telemt_desync_suppressed_total 5909
telemt_desync_frames_bucket_total{bucket="1_2"} 2133
telemt_desync_frames_bucket_total{bucket="3_10"} 3166
telemt_desync_frames_bucket_total{bucket="gt_10"} 3380
telemt_pool_swap_total 40
telemt_me_writer_close_signal_drop_total 540
telemt_me_writer_removed_unexpected_total 7021
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 6347
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 670
telemt_user_connections_total{user="hello"} 2287873
telemt_user_connections_current{user="hello"} 1599
telemt_user_octets_from_client{user="hello"} 36694220648 (34.17 GB)
telemt_user_octets_to_client{user="hello"} 660885931833 (615.50 GB)
telemt_user_msgs_from_client{user="hello"} 245686
telemt_user_msgs_to_client{user="hello"} 1753278
telemt_user_unique_ips_current{user="hello"} 595
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 106975.8 (29h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6466603
telemt_connections_bad_total 1108154
telemt_connections_current 1824
telemt_connections_me_current 1824
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 115898
telemt_upstream_connect_attempt_total 128658
telemt_upstream_connect_success_total 95367
telemt_upstream_connect_fail_total 33291
telemt_upstream_connect_attempts_per_request{bucket="1"} 128658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13043
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33291
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 79410
telemt_me_reconnect_success_total 13736
telemt_me_reader_eof_total 14783
telemt_me_idle_close_by_peer_total 14769
telemt_me_route_drop_no_conn_total 2839348
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4567335
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
telemt_desync_total 19926
telemt_desync_full_logged_total 6329
telemt_desync_suppressed_total 13597
telemt_desync_frames_bucket_total{bucket="1_2"} 3518
telemt_desync_frames_bucket_total{bucket="3_10"} 8238
telemt_desync_frames_bucket_total{bucket="gt_10"} 8170
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 14051
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 13711
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 315
telemt_user_connections_total{user="hello"} 4642406
telemt_user_connections_current{user="hello"} 1824
telemt_user_octets_from_client{user="hello"} 73817155096 (68.75 GB)
telemt_user_octets_to_client{user="hello"} 1804845020096 (1.64 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 726
telemt_user_unique_ips_recent_window{user="hello"} 223
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 53215.8 (14h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1061528
telemt_connections_bad_total 94408
telemt_connections_current 810
telemt_connections_me_current 810
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13496
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
telemt_me_route_drop_no_conn_total 473003
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
telemt_desync_total 1421
telemt_desync_full_logged_total 543
telemt_desync_suppressed_total 878
telemt_desync_frames_bucket_total{bucket="1_2"} 219
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
telemt_user_connections_total{user="hello"} 899412
telemt_user_connections_current{user="hello"} 809
telemt_user_octets_from_client{user="hello"} 7904097195 (7.36 GB)
telemt_user_octets_to_client{user="hello"} 146600745654 (136.53 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 53217.2 (14h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2142483
telemt_connections_bad_total 125963
telemt_connections_current 1622
telemt_connections_me_current 1622
telemt_handshake_timeouts_total 40004
telemt_upstream_connect_attempt_total 9613
telemt_upstream_connect_success_total 9548
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 9613
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4351
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6917
telemt_me_reconnect_success_total 6871
telemt_me_reader_eof_total 7254
telemt_me_idle_close_by_peer_total 7254
telemt_me_route_drop_no_conn_total 773117
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1824912
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9468
telemt_desync_full_logged_total 3057
telemt_desync_suppressed_total 6411
telemt_desync_frames_bucket_total{bucket="1_2"} 1831
telemt_desync_frames_bucket_total{bucket="3_10"} 3304
telemt_desync_frames_bucket_total{bucket="gt_10"} 4333
telemt_pool_swap_total 54
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 6967
telemt_me_writer_restored_same_endpoint_total 6854
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 1824011
telemt_user_connections_current{user="hello"} 1622
telemt_user_octets_from_client{user="hello"} 30843404184 (28.73 GB)
telemt_user_octets_to_client{user="hello"} 936864930032 (872.52 GB)
telemt_user_unique_ips_current{user="hello"} 629
telemt_user_unique_ips_recent_window{user="hello"} 174
```