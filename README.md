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

# Server Metrics 2026-03-20 04:32:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 40498.5 (11h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 752378
telemt_connections_bad_total 51357
telemt_connections_current 1058
telemt_connections_me_current 1058
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 17416
telemt_upstream_connect_attempt_total 8053
telemt_upstream_connect_success_total 7958
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 8053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3477
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 4885
telemt_me_reconnect_success_total 4843
telemt_me_reader_eof_total 5127
telemt_me_idle_close_by_peer_total 5126
telemt_me_route_drop_no_conn_total 211270
telemt_me_route_drop_channel_closed_total 68
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 599766
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3193
telemt_desync_full_logged_total 1137
telemt_desync_suppressed_total 2056
telemt_desync_frames_bucket_total{bucket="1_2"} 628
telemt_desync_frames_bucket_total{bucket="3_10"} 1225
telemt_desync_frames_bucket_total{bucket="gt_10"} 1340
telemt_pool_swap_total 44
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 4890
telemt_me_writer_restored_same_endpoint_total 4830
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 601174
telemt_user_connections_current{user="hello"} 1058
telemt_user_octets_from_client{user="hello"} 31949021228 (29.75 GB)
telemt_user_octets_to_client{user="hello"} 204308298849 (190.28 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 423
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 56954.1 (15h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3480245
telemt_connections_bad_total 279364
telemt_connections_current 2866
telemt_connections_me_current 2866
telemt_handshake_timeouts_total 75097
telemt_upstream_connect_attempt_total 10919
telemt_upstream_connect_success_total 10720
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 10919
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4571
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10901
telemt_me_reconnect_success_total 6651
telemt_me_reader_eof_total 7117
telemt_me_idle_close_by_peer_total 7117
telemt_me_route_drop_no_conn_total 1604050
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2877936
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12037
telemt_desync_full_logged_total 4017
telemt_desync_suppressed_total 8020
telemt_desync_frames_bucket_total{bucket="1_2"} 2302
telemt_desync_frames_bucket_total{bucket="3_10"} 4681
telemt_desync_frames_bucket_total{bucket="gt_10"} 5054
telemt_pool_swap_total 51
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 55
telemt_me_writer_removed_unexpected_total 6864
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6596
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 213
telemt_user_connections_total{user="hello"} 2877605
telemt_user_connections_current{user="hello"} 2866
telemt_user_octets_from_client{user="hello"} 43822967650 (40.81 GB)
telemt_user_octets_to_client{user="hello"} 1086056663986 (1011.47 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1099
telemt_user_unique_ips_recent_window{user="hello"} 385
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 56931.9 (15h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3215207
telemt_connections_bad_total 487003
telemt_connections_current 2358
telemt_connections_me_current 2358
telemt_handshake_timeouts_total 50686
telemt_upstream_connect_attempt_total 9300
telemt_upstream_connect_success_total 9235
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 9300
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4533
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7332
telemt_me_reconnect_success_total 6392
telemt_me_reader_eof_total 6730
telemt_me_idle_close_by_peer_total 6729
telemt_me_route_drop_no_conn_total 2003273
telemt_me_route_drop_channel_closed_total 178
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2246372
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8278
telemt_desync_full_logged_total 2549
telemt_desync_suppressed_total 5729
telemt_desync_frames_bucket_total{bucket="1_2"} 2042
telemt_desync_frames_bucket_total{bucket="3_10"} 3155
telemt_desync_frames_bucket_total{bucket="gt_10"} 3081
telemt_pool_swap_total 57
telemt_me_writer_close_signal_drop_total 74
telemt_me_writer_removed_unexpected_total 6457
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 6391
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 2241399
telemt_user_connections_current{user="hello"} 2358
telemt_user_octets_from_client{user="hello"} 34134054336 (31.79 GB)
telemt_user_octets_to_client{user="hello"} 893433661084 (832.07 GB)
telemt_user_unique_ips_current{user="hello"} 832
telemt_user_unique_ips_recent_window{user="hello"} 284
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 56919.8 (15h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2908610
telemt_connections_bad_total 220885
telemt_connections_current 2294
telemt_connections_me_current 2294
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 35634
telemt_upstream_connect_attempt_total 63277
telemt_upstream_connect_success_total 58719
telemt_upstream_connect_fail_total 4558
telemt_upstream_connect_attempts_per_request{bucket="1"} 63277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8511
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 551
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4558
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 9667
telemt_me_reconnect_success_total 6737
telemt_me_reader_eof_total 7031
telemt_me_idle_close_by_peer_total 7030
telemt_me_route_drop_no_conn_total 1979141
telemt_me_route_drop_channel_closed_total 56
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2357684
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8989
telemt_desync_full_logged_total 2874
telemt_desync_suppressed_total 6115
telemt_desync_frames_bucket_total{bucket="1_2"} 2180
telemt_desync_frames_bucket_total{bucket="3_10"} 3290
telemt_desync_frames_bucket_total{bucket="gt_10"} 3519
telemt_pool_swap_total 44
telemt_me_writer_close_signal_drop_total 541
telemt_me_writer_removed_unexpected_total 7417
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 6733
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 680
telemt_user_connections_total{user="hello"} 2404913
telemt_user_connections_current{user="hello"} 2294
telemt_user_octets_from_client{user="hello"} 38160470849 (35.54 GB)
telemt_user_octets_to_client{user="hello"} 717773357827 (668.48 GB)
telemt_user_msgs_from_client{user="hello"} 254085
telemt_user_msgs_to_client{user="hello"} 1776413
telemt_user_unique_ips_current{user="hello"} 810
telemt_user_unique_ips_recent_window{user="hello"} 284
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 110643.1 (30h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6659712
telemt_connections_bad_total 1176679
telemt_connections_current 2531
telemt_connections_me_current 2531
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 119039
telemt_upstream_connect_attempt_total 129230
telemt_upstream_connect_success_total 95934
telemt_upstream_connect_fail_total 33296
telemt_upstream_connect_attempts_per_request{bucket="1"} 129230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13310
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33296
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 79805
telemt_me_reconnect_success_total 14127
telemt_me_reader_eof_total 15198
telemt_me_idle_close_by_peer_total 15184
telemt_me_route_drop_no_conn_total 2877669
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4683031
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
telemt_desync_total 20260
telemt_desync_full_logged_total 6454
telemt_desync_suppressed_total 13806
telemt_desync_frames_bucket_total{bucket="1_2"} 3568
telemt_desync_frames_bucket_total{bucket="3_10"} 8384
telemt_desync_frames_bucket_total{bucket="gt_10"} 8308
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 14450
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 14102
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 323
telemt_user_connections_total{user="hello"} 4758101
telemt_user_connections_current{user="hello"} 2531
telemt_user_octets_from_client{user="hello"} 75379445892 (70.20 GB)
telemt_user_octets_to_client{user="hello"} 1864230557332 (1.70 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 928
telemt_user_unique_ips_recent_window{user="hello"} 336
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 56882.9 (15h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1350757
telemt_connections_bad_total 95242
telemt_connections_current 478
telemt_connections_me_current 478
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13802
telemt_upstream_connect_attempt_total 13771
telemt_upstream_connect_success_total 13441
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5581
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
telemt_me_route_drop_no_conn_total 473318
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
telemt_desync_total 1492
telemt_desync_full_logged_total 565
telemt_desync_suppressed_total 927
telemt_desync_frames_bucket_total{bucket="1_2"} 234
telemt_desync_frames_bucket_total{bucket="3_10"} 644
telemt_desync_frames_bucket_total{bucket="gt_10"} 614
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
telemt_user_connections_total{user="hello"} 1184686
telemt_user_connections_current{user="hello"} 478
telemt_user_octets_from_client{user="hello"} 8342428595 (7.77 GB)
telemt_user_octets_to_client{user="hello"} 146613788006 (136.54 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 56884.4 (15h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2275387
telemt_connections_bad_total 148505
telemt_connections_current 2261
telemt_connections_me_current 2261
telemt_handshake_timeouts_total 43054
telemt_upstream_connect_attempt_total 10242
telemt_upstream_connect_success_total 10176
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 10242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4654
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7373
telemt_me_reconnect_success_total 7324
telemt_me_reader_eof_total 7740
telemt_me_idle_close_by_peer_total 7740
telemt_me_route_drop_no_conn_total 813411
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1922545
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9792
telemt_desync_full_logged_total 3165
telemt_desync_suppressed_total 6627
telemt_desync_frames_bucket_total{bucket="1_2"} 1928
telemt_desync_frames_bucket_total{bucket="3_10"} 3427
telemt_desync_frames_bucket_total{bucket="gt_10"} 4437
telemt_pool_swap_total 58
telemt_me_writer_close_signal_drop_total 42
telemt_me_writer_removed_unexpected_total 7428
telemt_me_writer_restored_same_endpoint_total 7307
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 1921314
telemt_user_connections_current{user="hello"} 2261
telemt_user_octets_from_client{user="hello"} 41372505092 (38.53 GB)
telemt_user_octets_to_client{user="hello"} 1004055924400 (935.10 GB)
telemt_user_unique_ips_current{user="hello"} 804
telemt_user_unique_ips_recent_window{user="hello"} 243
```