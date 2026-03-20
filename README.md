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

# Server Metrics 2026-03-20 04:52:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 41721.1 (11h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 781126
telemt_connections_bad_total 52460
telemt_connections_current 1163
telemt_connections_me_current 1163
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 17736
telemt_upstream_connect_attempt_total 8277
telemt_upstream_connect_success_total 8181
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 8277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3585
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 5022
telemt_me_reconnect_success_total 4979
telemt_me_reader_eof_total 5273
telemt_me_idle_close_by_peer_total 5272
telemt_me_route_drop_no_conn_total 218660
telemt_me_route_drop_channel_closed_total 70
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 625658
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3349
telemt_desync_full_logged_total 1202
telemt_desync_suppressed_total 2147
telemt_desync_frames_bucket_total{bucket="1_2"} 643
telemt_desync_frames_bucket_total{bucket="3_10"} 1310
telemt_desync_frames_bucket_total{bucket="gt_10"} 1396
telemt_pool_swap_total 46
telemt_me_writer_close_signal_drop_total 43
telemt_me_writer_removed_unexpected_total 5026
telemt_me_writer_restored_same_endpoint_total 4966
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 627112
telemt_user_connections_current{user="hello"} 1163
telemt_user_octets_from_client{user="hello"} 32213180000 (30.00 GB)
telemt_user_octets_to_client{user="hello"} 214258269129 (199.54 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 438
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 58176.8 (16h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3573026
telemt_connections_bad_total 301360
telemt_connections_current 3185
telemt_connections_me_current 3185
telemt_handshake_timeouts_total 76867
telemt_upstream_connect_attempt_total 11075
telemt_upstream_connect_success_total 10872
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 11075
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4648
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 11008
telemt_me_reconnect_success_total 6758
telemt_me_reader_eof_total 7229
telemt_me_idle_close_by_peer_total 7229
telemt_me_route_drop_no_conn_total 1626727
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2941573
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12242
telemt_desync_full_logged_total 4093
telemt_desync_suppressed_total 8149
telemt_desync_frames_bucket_total{bucket="1_2"} 2322
telemt_desync_frames_bucket_total{bucket="3_10"} 4758
telemt_desync_frames_bucket_total{bucket="gt_10"} 5162
telemt_pool_swap_total 52
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 56
telemt_me_writer_removed_unexpected_total 6973
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6703
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 215
telemt_user_connections_total{user="hello"} 2941257
telemt_user_connections_current{user="hello"} 3185
telemt_user_octets_from_client{user="hello"} 44813762414 (41.74 GB)
telemt_user_octets_to_client{user="hello"} 1114024472898 (1.01 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1187
telemt_user_unique_ips_recent_window{user="hello"} 406
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 58154.5 (16h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3270181
telemt_connections_bad_total 490044
telemt_connections_current 2384
telemt_connections_me_current 2384
telemt_handshake_timeouts_total 51391
telemt_upstream_connect_attempt_total 9452
telemt_upstream_connect_success_total 9387
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 9452
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4757
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4613
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7441
telemt_me_reconnect_success_total 6500
telemt_me_reader_eof_total 6845
telemt_me_idle_close_by_peer_total 6844
telemt_me_route_drop_no_conn_total 2017927
telemt_me_route_drop_channel_closed_total 181
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2293236
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8456
telemt_desync_full_logged_total 2607
telemt_desync_suppressed_total 5849
telemt_desync_frames_bucket_total{bucket="1_2"} 2090
telemt_desync_frames_bucket_total{bucket="3_10"} 3229
telemt_desync_frames_bucket_total{bucket="gt_10"} 3137
telemt_pool_swap_total 58
telemt_me_writer_close_signal_drop_total 74
telemt_me_writer_removed_unexpected_total 6568
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 6499
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 2288266
telemt_user_connections_current{user="hello"} 2384
telemt_user_octets_from_client{user="hello"} 34790236072 (32.40 GB)
telemt_user_octets_to_client{user="hello"} 918900988928 (855.79 GB)
telemt_user_unique_ips_current{user="hello"} 889
telemt_user_unique_ips_recent_window{user="hello"} 295
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 58142.5 (16h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2960738
telemt_connections_bad_total 223700
telemt_connections_current 2313
telemt_connections_me_current 2313
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 37955
telemt_upstream_connect_attempt_total 63438
telemt_upstream_connect_success_total 58879
telemt_upstream_connect_fail_total 4559
telemt_upstream_connect_attempts_per_request{bucket="1"} 63438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49718
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8585
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 551
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4559
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 9785
telemt_me_reconnect_success_total 6852
telemt_me_reader_eof_total 7154
telemt_me_idle_close_by_peer_total 7153
telemt_me_route_drop_no_conn_total 2002552
telemt_me_route_drop_channel_closed_total 68
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2402754
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9170
telemt_desync_full_logged_total 2930
telemt_desync_suppressed_total 6240
telemt_desync_frames_bucket_total{bucket="1_2"} 2209
telemt_desync_frames_bucket_total{bucket="3_10"} 3363
telemt_desync_frames_bucket_total{bucket="gt_10"} 3598
telemt_pool_swap_total 45
telemt_me_writer_close_signal_drop_total 541
telemt_me_writer_removed_unexpected_total 7537
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 6848
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 685
telemt_user_connections_total{user="hello"} 2449942
telemt_user_connections_current{user="hello"} 2313
telemt_user_octets_from_client{user="hello"} 38723558609 (36.06 GB)
telemt_user_octets_to_client{user="hello"} 736076882387 (685.53 GB)
telemt_user_msgs_from_client{user="hello"} 254085
telemt_user_msgs_to_client{user="hello"} 1776413
telemt_user_unique_ips_current{user="hello"} 863
telemt_user_unique_ips_recent_window{user="hello"} 297
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 111865.6 (31h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6719446
telemt_connections_bad_total 1182988
telemt_connections_current 2806
telemt_connections_me_current 2806
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 119825
telemt_upstream_connect_attempt_total 129446
telemt_upstream_connect_success_total 96146
telemt_upstream_connect_fail_total 33300
telemt_upstream_connect_attempts_per_request{bucket="1"} 129446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13406
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33300
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 79931
telemt_me_reconnect_success_total 14252
telemt_me_reader_eof_total 15336
telemt_me_idle_close_by_peer_total 15322
telemt_me_route_drop_no_conn_total 2894729
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4733494
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
telemt_desync_total 20499
telemt_desync_full_logged_total 6519
telemt_desync_suppressed_total 13980
telemt_desync_frames_bucket_total{bucket="1_2"} 3629
telemt_desync_frames_bucket_total{bucket="3_10"} 8471
telemt_desync_frames_bucket_total{bucket="gt_10"} 8399
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 14579
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 14227
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 327
telemt_user_connections_total{user="hello"} 4808553
telemt_user_connections_current{user="hello"} 2806
telemt_user_octets_from_client{user="hello"} 76057322504 (70.83 GB)
telemt_user_octets_to_client{user="hello"} 1892300540984 (1.72 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 991
telemt_user_unique_ips_recent_window{user="hello"} 339
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 58105.6 (16h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1422988
telemt_connections_bad_total 102792
telemt_connections_current 752
telemt_connections_me_current 752
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 14051
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
telemt_me_route_drop_no_conn_total 473446
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
telemt_desync_total 1526
telemt_desync_full_logged_total 572
telemt_desync_suppressed_total 954
telemt_desync_frames_bucket_total{bucket="1_2"} 234
telemt_desync_frames_bucket_total{bucket="3_10"} 675
telemt_desync_frames_bucket_total{bucket="gt_10"} 617
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
telemt_user_connections_total{user="hello"} 1247711
telemt_user_connections_current{user="hello"} 752
telemt_user_octets_from_client{user="hello"} 8549153751 (7.96 GB)
telemt_user_octets_to_client{user="hello"} 146619063862 (136.55 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 181
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 58107.1 (16h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2336350
telemt_connections_bad_total 152440
telemt_connections_current 2508
telemt_connections_me_current 2508
telemt_handshake_timeouts_total 43579
telemt_upstream_connect_attempt_total 10441
telemt_upstream_connect_success_total 10375
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 10441
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4739
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7529
telemt_me_reconnect_success_total 7480
telemt_me_reader_eof_total 7903
telemt_me_idle_close_by_peer_total 7903
telemt_me_route_drop_no_conn_total 828697
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1964927
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9981
telemt_desync_full_logged_total 3231
telemt_desync_suppressed_total 6750
telemt_desync_frames_bucket_total{bucket="1_2"} 1955
telemt_desync_frames_bucket_total{bucket="3_10"} 3501
telemt_desync_frames_bucket_total{bucket="gt_10"} 4525
telemt_pool_swap_total 59
telemt_me_writer_close_signal_drop_total 42
telemt_me_writer_removed_unexpected_total 7586
telemt_me_writer_restored_same_endpoint_total 7463
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 1963624
telemt_user_connections_current{user="hello"} 2508
telemt_user_octets_from_client{user="hello"} 41931572056 (39.05 GB)
telemt_user_octets_to_client{user="hello"} 1033363396072 (962.39 GB)
telemt_user_unique_ips_current{user="hello"} 875
telemt_user_unique_ips_recent_window{user="hello"} 300
```