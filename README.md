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

# Server Metrics 2026-03-19 15:10:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 3985.1 (1h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123799
telemt_connections_bad_total 3738
telemt_connections_current 1538
telemt_connections_direct_current 1538
telemt_relay_adaptive_promotions_total 49
telemt_relay_adaptive_demotions_total 11546
telemt_relay_adaptive_hard_promotions_total 48
telemt_handshake_timeouts_total 1455
telemt_upstream_connect_attempt_total 110245
telemt_upstream_connect_success_total 110188
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 110243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4476
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 110186
telemt_user_connections_current{user="hello"} 1538
telemt_user_octets_from_client{user="hello"} 1839810331 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 25093382960 (23.37 GB)
telemt_user_msgs_from_client{user="hello"} 2123293
telemt_user_msgs_to_client{user="hello"} 2556624
telemt_user_unique_ips_current{user="hello"} 388
telemt_user_unique_ips_recent_window{user="hello"} 246
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 8859.1 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 962495
telemt_connections_bad_total 35893
telemt_connections_current 4118
telemt_connections_me_current 4118
telemt_handshake_timeouts_total 20443
telemt_upstream_connect_attempt_total 2944
telemt_upstream_connect_success_total 2920
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 2944
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 767
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 5429
telemt_me_reconnect_success_total 1213
telemt_me_reader_eof_total 1322
telemt_me_idle_close_by_peer_total 1322
telemt_me_route_drop_no_conn_total 706173
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 811944
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3051
telemt_desync_full_logged_total 961
telemt_desync_suppressed_total 2090
telemt_desync_frames_bucket_total{bucket="1_2"} 544
telemt_desync_frames_bucket_total{bucket="3_10"} 1204
telemt_desync_frames_bucket_total{bucket="gt_10"} 1303
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 27
telemt_me_writer_removed_unexpected_total 1335
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1158
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 812217
telemt_user_connections_current{user="hello"} 4118
telemt_user_octets_from_client{user="hello"} 10248546262 (9.54 GB)
telemt_user_octets_to_client{user="hello"} 221540311058 (206.33 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1397
telemt_user_unique_ips_recent_window{user="hello"} 665
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 8838.0 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 913234
telemt_connections_bad_total 100849
telemt_connections_current 2946
telemt_connections_me_current 2946
telemt_handshake_timeouts_total 8761
telemt_upstream_connect_attempt_total 1468
telemt_upstream_connect_success_total 1455
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 1468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 636
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1885
telemt_me_reconnect_success_total 978
telemt_me_reader_eof_total 944
telemt_me_idle_close_by_peer_total 943
telemt_me_route_drop_no_conn_total 831247
telemt_me_route_drop_channel_closed_total 76
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 697855
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2428
telemt_desync_full_logged_total 649
telemt_desync_suppressed_total 1779
telemt_desync_frames_bucket_total{bucket="1_2"} 695
telemt_desync_frames_bucket_total{bucket="3_10"} 906
telemt_desync_frames_bucket_total{bucket="gt_10"} 827
telemt_pool_swap_total 5
telemt_me_writer_close_signal_drop_total 32
telemt_me_writer_removed_unexpected_total 946
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 977
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 695080
telemt_user_connections_current{user="hello"} 2946
telemt_user_octets_from_client{user="hello"} 7255485264 (6.76 GB)
telemt_user_octets_to_client{user="hello"} 187259108660 (174.40 GB)
telemt_user_unique_ips_current{user="hello"} 1061
telemt_user_unique_ips_recent_window{user="hello"} 468
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 8825.0 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 736941
telemt_connections_bad_total 46093
telemt_connections_current 2917
telemt_connections_me_current 2917
telemt_handshake_timeouts_total 11440
telemt_upstream_connect_attempt_total 10506
telemt_upstream_connect_success_total 10004
telemt_upstream_connect_fail_total 502
telemt_upstream_connect_attempts_per_request{bucket="1"} 10506
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1752
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 502
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 1379
telemt_me_reconnect_success_total 1067
telemt_me_reader_eof_total 1054
telemt_me_idle_close_by_peer_total 1053
telemt_me_route_drop_no_conn_total 495378
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 615954
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2742
telemt_desync_full_logged_total 922
telemt_desync_suppressed_total 1820
telemt_desync_frames_bucket_total{bucket="1_2"} 572
telemt_desync_frames_bucket_total{bucket="3_10"} 1059
telemt_desync_frames_bucket_total{bucket="gt_10"} 1111
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 77
telemt_me_writer_removed_unexpected_total 1190
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 1063
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 623901
telemt_user_connections_current{user="hello"} 2917
telemt_user_octets_from_client{user="hello"} 13011111623 (12.12 GB)
telemt_user_octets_to_client{user="hello"} 141715171984 (131.98 GB)
telemt_user_msgs_from_client{user="hello"} 16739
telemt_user_msgs_to_client{user="hello"} 18599
telemt_user_unique_ips_current{user="hello"} 997
telemt_user_unique_ips_recent_window{user="hello"} 491
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 62548.5 (17h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4403801
telemt_connections_bad_total 815918
telemt_connections_current 3779
telemt_connections_me_current 3779
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 85073
telemt_upstream_connect_attempt_total 63051
telemt_upstream_connect_success_total 60564
telemt_upstream_connect_fail_total 2487
telemt_upstream_connect_attempts_per_request{bucket="1"} 63051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7536
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1022
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2487
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 73635
telemt_me_reconnect_success_total 8237
telemt_me_reader_eof_total 8667
telemt_me_idle_close_by_peer_total 8664
telemt_me_route_drop_no_conn_total 2092649
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3029457
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
telemt_desync_total 13063
telemt_desync_full_logged_total 4018
telemt_desync_suppressed_total 9045
telemt_desync_frames_bucket_total{bucket="1_2"} 2207
telemt_desync_frames_bucket_total{bucket="3_10"} 5600
telemt_desync_frames_bucket_total{bucket="gt_10"} 5256
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 8454
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 8213
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 217
telemt_user_connections_total{user="hello"} 3078088
telemt_user_connections_current{user="hello"} 3779
telemt_user_octets_from_client{user="hello"} 48654984583 (45.31 GB)
telemt_user_octets_to_client{user="hello"} 1088810939204 (1014.03 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1207
telemt_user_unique_ips_recent_window{user="hello"} 595
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 8790.7 (2h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 199721
telemt_connections_bad_total 11697
telemt_connections_current 1023
telemt_connections_me_current 1023
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 6237
telemt_upstream_connect_attempt_total 4314
telemt_upstream_connect_success_total 4177
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 4314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2485
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_reconnect_attempts_total 1194
telemt_me_reconnect_success_total 1164
telemt_me_reader_eof_total 1151
telemt_me_idle_close_by_peer_total 1151
telemt_me_route_drop_no_conn_total 127994
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 169624
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 464
telemt_me_writer_pick_total{mode="p2c",result="full"} 2833
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_writer_pick_blocking_fallback_total 3285
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 516
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 355
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 210
telemt_desync_frames_bucket_total{bucket="gt_10"} 225
telemt_pool_swap_total 6
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 46
telemt_me_writer_removed_unexpected_total 1135
telemt_me_writer_restored_same_endpoint_total 1155
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 179
telemt_me_async_recovery_trigger_total 1239
telemt_user_connections_total{user="hello"} 172239
telemt_user_connections_current{user="hello"} 1023
telemt_user_octets_from_client{user="hello"} 2399721176 (2.23 GB)
telemt_user_octets_to_client{user="hello"} 44283219082 (41.24 GB)
telemt_user_msgs_from_client{user="hello"} 7378
telemt_user_msgs_to_client{user="hello"} 12667
telemt_user_unique_ips_current{user="hello"} 361
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 8789.6 (2h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 601243
telemt_connections_bad_total 39308
telemt_connections_current 3032
telemt_connections_me_current 3032
telemt_handshake_timeouts_total 10628
telemt_upstream_connect_attempt_total 1444
telemt_upstream_connect_success_total 1434
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1444
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 630
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 965
telemt_me_reconnect_success_total 947
telemt_me_reader_eof_total 975
telemt_me_idle_close_by_peer_total 975
telemt_me_route_drop_no_conn_total 212825
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 518974
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2884
telemt_desync_full_logged_total 869
telemt_desync_suppressed_total 2015
telemt_desync_frames_bucket_total{bucket="1_2"} 571
telemt_desync_frames_bucket_total{bucket="3_10"} 951
telemt_desync_frames_bucket_total{bucket="gt_10"} 1362
telemt_pool_swap_total 6
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 974
telemt_me_writer_restored_same_endpoint_total 930
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 518594
telemt_user_connections_current{user="hello"} 3032
telemt_user_octets_from_client{user="hello"} 7456284164 (6.94 GB)
telemt_user_octets_to_client{user="hello"} 218769369788 (203.74 GB)
telemt_user_unique_ips_current{user="hello"} 1023
telemt_user_unique_ips_recent_window{user="hello"} 465
```