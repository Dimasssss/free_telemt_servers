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

# Server Metrics 2026-03-20 04:22:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 39887.6 (11h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 738157
telemt_connections_bad_total 50795
telemt_connections_current 1036
telemt_connections_me_current 1036
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 17035
telemt_upstream_connect_attempt_total 8001
telemt_upstream_connect_success_total 7906
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 8001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4429
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3449
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 4833
telemt_me_reconnect_success_total 4792
telemt_me_reader_eof_total 5074
telemt_me_idle_close_by_peer_total 5073
telemt_me_route_drop_no_conn_total 207763
telemt_me_route_drop_channel_closed_total 68
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 586961
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3069
telemt_desync_full_logged_total 1099
telemt_desync_suppressed_total 1970
telemt_desync_frames_bucket_total{bucket="1_2"} 606
telemt_desync_frames_bucket_total{bucket="3_10"} 1172
telemt_desync_frames_bucket_total{bucket="gt_10"} 1291
telemt_pool_swap_total 44
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 4837
telemt_me_writer_restored_same_endpoint_total 4779
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 588380
telemt_user_connections_current{user="hello"} 1036
telemt_user_octets_from_client{user="hello"} 31835703416 (29.65 GB)
telemt_user_octets_to_client{user="hello"} 199950142317 (186.22 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 437
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 56343.4 (15h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3436422
telemt_connections_bad_total 268144
telemt_connections_current 2685
telemt_connections_me_current 2685
telemt_handshake_timeouts_total 74312
telemt_upstream_connect_attempt_total 10817
telemt_upstream_connect_success_total 10620
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 10817
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4521
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10844
telemt_me_reconnect_success_total 6594
telemt_me_reader_eof_total 7055
telemt_me_idle_close_by_peer_total 7055
telemt_me_route_drop_no_conn_total 1593302
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2847172
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11965
telemt_desync_full_logged_total 3987
telemt_desync_suppressed_total 7978
telemt_desync_frames_bucket_total{bucket="1_2"} 2298
telemt_desync_frames_bucket_total{bucket="3_10"} 4650
telemt_desync_frames_bucket_total{bucket="gt_10"} 5017
telemt_pool_swap_total 50
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 54
telemt_me_writer_removed_unexpected_total 6806
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6539
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 2846860
telemt_user_connections_current{user="hello"} 2685
telemt_user_octets_from_client{user="hello"} 43414622954 (40.43 GB)
telemt_user_octets_to_client{user="hello"} 1073738352510 (1000.00 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1064
telemt_user_unique_ips_recent_window{user="hello"} 346
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 56321.4 (15h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3192814
telemt_connections_bad_total 486224
telemt_connections_current 2179
telemt_connections_me_current 2179
telemt_handshake_timeouts_total 50505
telemt_upstream_connect_attempt_total 9189
telemt_upstream_connect_success_total 9124
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 9189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4479
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7264
telemt_me_reconnect_success_total 6326
telemt_me_reader_eof_total 6657
telemt_me_idle_close_by_peer_total 6656
telemt_me_route_drop_no_conn_total 1996193
telemt_me_route_drop_channel_closed_total 177
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2225991
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8198
telemt_desync_full_logged_total 2523
telemt_desync_suppressed_total 5675
telemt_desync_frames_bucket_total{bucket="1_2"} 2027
telemt_desync_frames_bucket_total{bucket="3_10"} 3116
telemt_desync_frames_bucket_total{bucket="gt_10"} 3055
telemt_pool_swap_total 56
telemt_me_writer_close_signal_drop_total 74
telemt_me_writer_removed_unexpected_total 6390
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 6325
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 2221018
telemt_user_connections_current{user="hello"} 2179
telemt_user_octets_from_client{user="hello"} 33764026164 (31.45 GB)
telemt_user_octets_to_client{user="hello"} 882354979312 (821.76 GB)
telemt_user_unique_ips_current{user="hello"} 790
telemt_user_unique_ips_recent_window{user="hello"} 252
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 56309.1 (15h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2883705
telemt_connections_bad_total 219844
telemt_connections_current 2039
telemt_connections_me_current 2039
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 34847
telemt_upstream_connect_attempt_total 63177
telemt_upstream_connect_success_total 58622
telemt_upstream_connect_fail_total 4555
telemt_upstream_connect_attempts_per_request{bucket="1"} 63177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8472
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 551
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4555
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 9612
telemt_me_reconnect_success_total 6684
telemt_me_reader_eof_total 6974
telemt_me_idle_close_by_peer_total 6973
telemt_me_route_drop_no_conn_total 1955473
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2335190
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8940
telemt_desync_full_logged_total 2856
telemt_desync_suppressed_total 6084
telemt_desync_frames_bucket_total{bucket="1_2"} 2172
telemt_desync_frames_bucket_total{bucket="3_10"} 3264
telemt_desync_frames_bucket_total{bucket="gt_10"} 3504
telemt_pool_swap_total 43
telemt_me_writer_close_signal_drop_total 540
telemt_me_writer_removed_unexpected_total 7364
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 6680
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 680
telemt_user_connections_total{user="hello"} 2382629
telemt_user_connections_current{user="hello"} 2039
telemt_user_octets_from_client{user="hello"} 37735376793 (35.14 GB)
telemt_user_octets_to_client{user="hello"} 707371598583 (658.79 GB)
telemt_user_msgs_from_client{user="hello"} 254085
telemt_user_msgs_to_client{user="hello"} 1776413
telemt_user_unique_ips_current{user="hello"} 702
telemt_user_unique_ips_recent_window{user="hello"} 243
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 110032.3 (30h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6623028
telemt_connections_bad_total 1164514
telemt_connections_current 2463
telemt_connections_me_current 2463
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 118555
telemt_upstream_connect_attempt_total 129181
telemt_upstream_connect_success_total 95885
telemt_upstream_connect_fail_total 33296
telemt_upstream_connect_attempts_per_request{bucket="1"} 129181
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13282
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33296
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 79756
telemt_me_reconnect_success_total 14078
telemt_me_reader_eof_total 15149
telemt_me_idle_close_by_peer_total 15135
telemt_me_route_drop_no_conn_total 2870723
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4659684
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
telemt_desync_total 20192
telemt_desync_full_logged_total 6426
telemt_desync_suppressed_total 13766
telemt_desync_frames_bucket_total{bucket="1_2"} 3560
telemt_desync_frames_bucket_total{bucket="3_10"} 8365
telemt_desync_frames_bucket_total{bucket="gt_10"} 8267
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 14401
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 14053
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 323
telemt_user_connections_total{user="hello"} 4734754
telemt_user_connections_current{user="hello"} 2463
telemt_user_octets_from_client{user="hello"} 75078023648 (69.92 GB)
telemt_user_octets_to_client{user="hello"} 1853203878684 (1.69 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 892
telemt_user_unique_ips_recent_window{user="hello"} 290
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 56272.3 (15h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1316585
telemt_connections_bad_total 94961
telemt_connections_current 943
telemt_connections_me_current 943
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13779
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
telemt_me_route_drop_no_conn_total 473269
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
telemt_desync_total 1483
telemt_desync_full_logged_total 562
telemt_desync_suppressed_total 921
telemt_desync_frames_bucket_total{bucket="1_2"} 234
telemt_desync_frames_bucket_total{bucket="3_10"} 637
telemt_desync_frames_bucket_total{bucket="gt_10"} 612
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
telemt_user_connections_total{user="hello"} 1151414
telemt_user_connections_current{user="hello"} 943
telemt_user_octets_from_client{user="hello"} 8265778947 (7.70 GB)
telemt_user_octets_to_client{user="hello"} 146611719098 (136.54 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 174
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 56273.6 (15h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2251246
telemt_connections_bad_total 147719
telemt_connections_current 2223
telemt_connections_me_current 2223
telemt_handshake_timeouts_total 42653
telemt_upstream_connect_attempt_total 10142
telemt_upstream_connect_success_total 10076
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 10142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4614
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7316
telemt_me_reconnect_success_total 7268
telemt_me_reader_eof_total 7678
telemt_me_idle_close_by_peer_total 7678
telemt_me_route_drop_no_conn_total 808091
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1904922
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9733
telemt_desync_full_logged_total 3142
telemt_desync_suppressed_total 6591
telemt_desync_frames_bucket_total{bucket="1_2"} 1907
telemt_desync_frames_bucket_total{bucket="3_10"} 3407
telemt_desync_frames_bucket_total{bucket="gt_10"} 4419
telemt_pool_swap_total 57
telemt_me_writer_close_signal_drop_total 42
telemt_me_writer_removed_unexpected_total 7370
telemt_me_writer_restored_same_endpoint_total 7251
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 1903688
telemt_user_connections_current{user="hello"} 2223
telemt_user_octets_from_client{user="hello"} 40922874036 (38.11 GB)
telemt_user_octets_to_client{user="hello"} 993299242092 (925.08 GB)
telemt_user_unique_ips_current{user="hello"} 778
telemt_user_unique_ips_recent_window{user="hello"} 220
```