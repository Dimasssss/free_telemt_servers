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

# Server Metrics 2026-03-20 04:42:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 41109.5 (11h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 766869
telemt_connections_bad_total 51903
telemt_connections_current 1169
telemt_connections_me_current 1169
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 17675
telemt_upstream_connect_attempt_total 8165
telemt_upstream_connect_success_total 8070
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 8165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3532
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 4954
telemt_me_reconnect_success_total 4912
telemt_me_reader_eof_total 5200
telemt_me_idle_close_by_peer_total 5199
telemt_me_route_drop_no_conn_total 215244
telemt_me_route_drop_channel_closed_total 70
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 612649
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3305
telemt_desync_full_logged_total 1179
telemt_desync_suppressed_total 2126
telemt_desync_frames_bucket_total{bucket="1_2"} 642
telemt_desync_frames_bucket_total{bucket="3_10"} 1283
telemt_desync_frames_bucket_total{bucket="gt_10"} 1380
telemt_pool_swap_total 45
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 4959
telemt_me_writer_restored_same_endpoint_total 4899
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 614072
telemt_user_connections_current{user="hello"} 1169
telemt_user_octets_from_client{user="hello"} 32072556064 (29.87 GB)
telemt_user_octets_to_client{user="hello"} 208900245665 (194.55 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 461
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 57565.5 (15h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3525197
telemt_connections_bad_total 290010
telemt_connections_current 3029
telemt_connections_me_current 3029
telemt_handshake_timeouts_total 76178
telemt_upstream_connect_attempt_total 10957
telemt_upstream_connect_success_total 10758
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 10957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4595
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10939
telemt_me_reconnect_success_total 6689
telemt_me_reader_eof_total 7157
telemt_me_idle_close_by_peer_total 7157
telemt_me_route_drop_no_conn_total 1615644
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2909108
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12121
telemt_desync_full_logged_total 4052
telemt_desync_suppressed_total 8069
telemt_desync_frames_bucket_total{bucket="1_2"} 2313
telemt_desync_frames_bucket_total{bucket="3_10"} 4707
telemt_desync_frames_bucket_total{bucket="gt_10"} 5101
telemt_pool_swap_total 51
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 55
telemt_me_writer_removed_unexpected_total 6904
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6634
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 215
telemt_user_connections_total{user="hello"} 2908784
telemt_user_connections_current{user="hello"} 3029
telemt_user_octets_from_client{user="hello"} 44191339266 (41.16 GB)
telemt_user_octets_to_client{user="hello"} 1099891210778 (1.00 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1134
telemt_user_unique_ips_recent_window{user="hello"} 420
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 57543.5 (15h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3241296
telemt_connections_bad_total 487630
telemt_connections_current 2318
telemt_connections_me_current 2318
telemt_handshake_timeouts_total 50865
telemt_upstream_connect_attempt_total 9338
telemt_upstream_connect_success_total 9273
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 9338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7370
telemt_me_reconnect_success_total 6430
telemt_me_reader_eof_total 6770
telemt_me_idle_close_by_peer_total 6769
telemt_me_route_drop_no_conn_total 2010956
telemt_me_route_drop_channel_closed_total 179
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2269982
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8383
telemt_desync_full_logged_total 2581
telemt_desync_suppressed_total 5802
telemt_desync_frames_bucket_total{bucket="1_2"} 2072
telemt_desync_frames_bucket_total{bucket="3_10"} 3196
telemt_desync_frames_bucket_total{bucket="gt_10"} 3115
telemt_pool_swap_total 57
telemt_me_writer_close_signal_drop_total 74
telemt_me_writer_removed_unexpected_total 6497
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 6429
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 2265009
telemt_user_connections_current{user="hello"} 2318
telemt_user_octets_from_client{user="hello"} 34453215480 (32.09 GB)
telemt_user_octets_to_client{user="hello"} 906493913548 (844.24 GB)
telemt_user_unique_ips_current{user="hello"} 853
telemt_user_unique_ips_recent_window{user="hello"} 285
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 57531.1 (15h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2934783
telemt_connections_bad_total 222385
telemt_connections_current 2380
telemt_connections_me_current 2380
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 37152
telemt_upstream_connect_attempt_total 63325
telemt_upstream_connect_success_total 58766
telemt_upstream_connect_fail_total 4559
telemt_upstream_connect_attempts_per_request{bucket="1"} 63325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8534
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 551
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4559
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 9715
telemt_me_reconnect_success_total 6783
telemt_me_reader_eof_total 7080
telemt_me_idle_close_by_peer_total 7079
telemt_me_route_drop_no_conn_total 1993829
telemt_me_route_drop_channel_closed_total 67
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2379904
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9103
telemt_desync_full_logged_total 2906
telemt_desync_suppressed_total 6197
telemt_desync_frames_bucket_total{bucket="1_2"} 2198
telemt_desync_frames_bucket_total{bucket="3_10"} 3344
telemt_desync_frames_bucket_total{bucket="gt_10"} 3561
telemt_pool_swap_total 44
telemt_me_writer_close_signal_drop_total 541
telemt_me_writer_removed_unexpected_total 7466
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 6779
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 683
telemt_user_connections_total{user="hello"} 2427096
telemt_user_connections_current{user="hello"} 2380
telemt_user_octets_from_client{user="hello"} 38437412221 (35.80 GB)
telemt_user_octets_to_client{user="hello"} 726739911223 (676.83 GB)
telemt_user_msgs_from_client{user="hello"} 254085
telemt_user_msgs_to_client{user="hello"} 1776413
telemt_user_unique_ips_current{user="hello"} 878
telemt_user_unique_ips_recent_window{user="hello"} 336
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 111254.2 (30h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6688372
telemt_connections_bad_total 1179214
telemt_connections_current 2714
telemt_connections_me_current 2714
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 119442
telemt_upstream_connect_attempt_total 129349
telemt_upstream_connect_success_total 96050
telemt_upstream_connect_fail_total 33299
telemt_upstream_connect_attempts_per_request{bucket="1"} 129349
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81251
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13362
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33299
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 79878
telemt_me_reconnect_success_total 14200
telemt_me_reader_eof_total 15277
telemt_me_idle_close_by_peer_total 15263
telemt_me_route_drop_no_conn_total 2886303
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4707782
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
telemt_desync_total 20357
telemt_desync_full_logged_total 6480
telemt_desync_suppressed_total 13877
telemt_desync_frames_bucket_total{bucket="1_2"} 3602
telemt_desync_frames_bucket_total{bucket="3_10"} 8423
telemt_desync_frames_bucket_total{bucket="gt_10"} 8332
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 14523
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 14175
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 323
telemt_user_connections_total{user="hello"} 4782845
telemt_user_connections_current{user="hello"} 2714
telemt_user_octets_from_client{user="hello"} 75692812464 (70.49 GB)
telemt_user_octets_to_client{user="hello"} 1878474960480 (1.71 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 953
telemt_user_unique_ips_recent_window{user="hello"} 349
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 57494.1 (15h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1393908
telemt_connections_bad_total 101961
telemt_connections_current 584
telemt_connections_me_current 584
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13991
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
telemt_me_route_drop_no_conn_total 473338
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
telemt_desync_total 1525
telemt_desync_full_logged_total 571
telemt_desync_suppressed_total 954
telemt_desync_frames_bucket_total{bucket="1_2"} 234
telemt_desync_frames_bucket_total{bucket="3_10"} 674
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
telemt_user_connections_total{user="hello"} 1219954
telemt_user_connections_current{user="hello"} 584
telemt_user_octets_from_client{user="hello"} 8430549599 (7.85 GB)
telemt_user_octets_to_client{user="hello"} 146616209274 (136.55 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 57495.6 (15h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2306016
telemt_connections_bad_total 150881
telemt_connections_current 2356
telemt_connections_me_current 2356
telemt_handshake_timeouts_total 43365
telemt_upstream_connect_attempt_total 10305
telemt_upstream_connect_success_total 10239
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 10305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4681
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7436
telemt_me_reconnect_success_total 7387
telemt_me_reader_eof_total 7803
telemt_me_idle_close_by_peer_total 7803
telemt_me_route_drop_no_conn_total 822035
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1943327
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9867
telemt_desync_full_logged_total 3194
telemt_desync_suppressed_total 6673
telemt_desync_frames_bucket_total{bucket="1_2"} 1940
telemt_desync_frames_bucket_total{bucket="3_10"} 3457
telemt_desync_frames_bucket_total{bucket="gt_10"} 4470
telemt_pool_swap_total 58
telemt_me_writer_close_signal_drop_total 42
telemt_me_writer_removed_unexpected_total 7491
telemt_me_writer_restored_same_endpoint_total 7370
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 1942028
telemt_user_connections_current{user="hello"} 2356
telemt_user_octets_from_client{user="hello"} 41619388392 (38.76 GB)
telemt_user_octets_to_client{user="hello"} 1018380163640 (948.44 GB)
telemt_user_unique_ips_current{user="hello"} 824
telemt_user_unique_ips_recent_window{user="hello"} 281
```