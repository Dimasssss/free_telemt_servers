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

# Server Metrics 2026-03-20 04:17:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 39582.2 (10h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 731905
telemt_connections_bad_total 50553
telemt_connections_current 1114
telemt_connections_me_current 1114
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 16726
telemt_upstream_connect_attempt_total 7913
telemt_upstream_connect_success_total 7818
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 7913
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4381
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3409
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 4788
telemt_me_reconnect_success_total 4747
telemt_me_reader_eof_total 5025
telemt_me_idle_close_by_peer_total 5024
telemt_me_route_drop_no_conn_total 206082
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 581583
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3037
telemt_desync_full_logged_total 1086
telemt_desync_suppressed_total 1951
telemt_desync_frames_bucket_total{bucket="1_2"} 601
telemt_desync_frames_bucket_total{bucket="3_10"} 1161
telemt_desync_frames_bucket_total{bucket="gt_10"} 1275
telemt_pool_swap_total 43
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 4792
telemt_me_writer_restored_same_endpoint_total 4734
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 582987
telemt_user_connections_current{user="hello"} 1114
telemt_user_octets_from_client{user="hello"} 31799850804 (29.62 GB)
telemt_user_octets_to_client{user="hello"} 198463948469 (184.83 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 433
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 56037.7 (15h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3415492
telemt_connections_bad_total 261882
telemt_connections_current 2682
telemt_connections_me_current 2682
telemt_handshake_timeouts_total 73712
telemt_upstream_connect_attempt_total 10788
telemt_upstream_connect_success_total 10591
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 10788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4504
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10815
telemt_me_reconnect_success_total 6565
telemt_me_reader_eof_total 7026
telemt_me_idle_close_by_peer_total 7026
telemt_me_route_drop_no_conn_total 1588489
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2833597
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11926
telemt_desync_full_logged_total 3968
telemt_desync_suppressed_total 7958
telemt_desync_frames_bucket_total{bucket="1_2"} 2292
telemt_desync_frames_bucket_total{bucket="3_10"} 4639
telemt_desync_frames_bucket_total{bucket="gt_10"} 4995
telemt_pool_swap_total 50
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 54
telemt_me_writer_removed_unexpected_total 6777
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6510
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 2833287
telemt_user_connections_current{user="hello"} 2682
telemt_user_octets_from_client{user="hello"} 43248130458 (40.28 GB)
telemt_user_octets_to_client{user="hello"} 1068009432650 (994.66 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1037
telemt_user_unique_ips_recent_window{user="hello"} 342
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 56016.1 (15h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3179572
telemt_connections_bad_total 485710
telemt_connections_current 2144
telemt_connections_me_current 2144
telemt_handshake_timeouts_total 50457
telemt_upstream_connect_attempt_total 9155
telemt_upstream_connect_success_total 9090
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 9155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4459
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7230
telemt_me_reconnect_success_total 6292
telemt_me_reader_eof_total 6623
telemt_me_idle_close_by_peer_total 6622
telemt_me_route_drop_no_conn_total 1993081
telemt_me_route_drop_channel_closed_total 177
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2216040
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8162
telemt_desync_full_logged_total 2514
telemt_desync_suppressed_total 5648
telemt_desync_frames_bucket_total{bucket="1_2"} 2018
telemt_desync_frames_bucket_total{bucket="3_10"} 3097
telemt_desync_frames_bucket_total{bucket="gt_10"} 3047
telemt_pool_swap_total 56
telemt_me_writer_close_signal_drop_total 73
telemt_me_writer_removed_unexpected_total 6356
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 6291
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 2211068
telemt_user_connections_current{user="hello"} 2144
telemt_user_octets_from_client{user="hello"} 33605544664 (31.30 GB)
telemt_user_octets_to_client{user="hello"} 875362195228 (815.24 GB)
telemt_user_unique_ips_current{user="hello"} 810
telemt_user_unique_ips_recent_window{user="hello"} 271
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 56003.6 (15h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2868770
telemt_connections_bad_total 219571
telemt_connections_current 2012
telemt_connections_me_current 2012
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 34644
telemt_upstream_connect_attempt_total 61698
telemt_upstream_connect_success_total 57192
telemt_upstream_connect_fail_total 4506
telemt_upstream_connect_attempts_per_request{bucket="1"} 61698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8422
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 550
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4506
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 9584
telemt_me_reconnect_success_total 6661
telemt_me_reader_eof_total 6949
telemt_me_idle_close_by_peer_total 6948
telemt_me_route_drop_no_conn_total 1950724
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2322772
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8917
telemt_desync_full_logged_total 2848
telemt_desync_suppressed_total 6069
telemt_desync_frames_bucket_total{bucket="1_2"} 2168
telemt_desync_frames_bucket_total{bucket="3_10"} 3258
telemt_desync_frames_bucket_total{bucket="gt_10"} 3491
telemt_pool_swap_total 43
telemt_me_writer_close_signal_drop_total 540
telemt_me_writer_removed_unexpected_total 7339
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 6657
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 678
telemt_user_connections_total{user="hello"} 2368845
telemt_user_connections_current{user="hello"} 2012
telemt_user_octets_from_client{user="hello"} 37586407870 (35.01 GB)
telemt_user_octets_to_client{user="hello"} 702643694247 (654.39 GB)
telemt_user_msgs_from_client{user="hello"} 251914
telemt_user_msgs_to_client{user="hello"} 1773933
telemt_user_unique_ips_current{user="hello"} 747
telemt_user_unique_ips_recent_window{user="hello"} 232
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 109727.0 (30h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6605125
telemt_connections_bad_total 1158332
telemt_connections_current 2501
telemt_connections_me_current 2501
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 118137
telemt_upstream_connect_attempt_total 129097
telemt_upstream_connect_success_total 95804
telemt_upstream_connect_fail_total 33293
telemt_upstream_connect_attempts_per_request{bucket="1"} 129097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13248
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33293
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 79718
telemt_me_reconnect_success_total 14041
telemt_me_reader_eof_total 15107
telemt_me_idle_close_by_peer_total 15093
telemt_me_route_drop_no_conn_total 2866344
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4648839
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
telemt_desync_total 20159
telemt_desync_full_logged_total 6417
telemt_desync_suppressed_total 13742
telemt_desync_frames_bucket_total{bucket="1_2"} 3554
telemt_desync_frames_bucket_total{bucket="3_10"} 8351
telemt_desync_frames_bucket_total{bucket="gt_10"} 8254
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 14363
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 14016
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 322
telemt_user_connections_total{user="hello"} 4723908
telemt_user_connections_current{user="hello"} 2501
telemt_user_octets_from_client{user="hello"} 74892603360 (69.75 GB)
telemt_user_octets_to_client{user="hello"} 1845214918948 (1.68 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 899
telemt_user_unique_ips_recent_window{user="hello"} 318
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 55966.9 (15h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1295817
telemt_connections_bad_total 94850
telemt_connections_current 638
telemt_connections_me_current 638
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13746
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
telemt_me_route_drop_no_conn_total 473209
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
telemt_desync_total 1474
telemt_desync_full_logged_total 558
telemt_desync_suppressed_total 916
telemt_desync_frames_bucket_total{bucket="1_2"} 233
telemt_desync_frames_bucket_total{bucket="3_10"} 629
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
telemt_user_connections_total{user="hello"} 1130896
telemt_user_connections_current{user="hello"} 638
telemt_user_octets_from_client{user="hello"} 8230698923 (7.67 GB)
telemt_user_octets_to_client{user="hello"} 146610450462 (136.54 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 55968.3 (15h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2240290
telemt_connections_bad_total 146565
telemt_connections_current 2379
telemt_connections_me_current 2379
telemt_handshake_timeouts_total 42511
telemt_upstream_connect_attempt_total 10097
telemt_upstream_connect_success_total 10031
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 10097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5405
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4589
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7271
telemt_me_reconnect_success_total 7223
telemt_me_reader_eof_total 7633
telemt_me_idle_close_by_peer_total 7633
telemt_me_route_drop_no_conn_total 805299
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1896088
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9690
telemt_desync_full_logged_total 3126
telemt_desync_suppressed_total 6564
telemt_desync_frames_bucket_total{bucket="1_2"} 1892
telemt_desync_frames_bucket_total{bucket="3_10"} 3396
telemt_desync_frames_bucket_total{bucket="gt_10"} 4402
telemt_pool_swap_total 57
telemt_me_writer_close_signal_drop_total 42
telemt_me_writer_removed_unexpected_total 7325
telemt_me_writer_restored_same_endpoint_total 7206
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 1894904
telemt_user_connections_current{user="hello"} 2379
telemt_user_octets_from_client{user="hello"} 40740080096 (37.94 GB)
telemt_user_octets_to_client{user="hello"} 988225551344 (920.36 GB)
telemt_user_unique_ips_current{user="hello"} 800
telemt_user_unique_ips_recent_window{user="hello"} 244
```