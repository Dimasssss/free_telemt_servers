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

# Server Metrics 2026-03-20 02:14:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 32243.7 (8h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 602893
telemt_connections_bad_total 38394
telemt_connections_current 869
telemt_connections_me_current 869
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 10075
telemt_upstream_connect_attempt_total 6710
telemt_upstream_connect_success_total 6624
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 6710
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3777
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2819
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 3940
telemt_me_reconnect_success_total 3904
telemt_me_reader_eof_total 4120
telemt_me_idle_close_by_peer_total 4119
telemt_me_route_drop_no_conn_total 172265
telemt_me_route_drop_channel_closed_total 58
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 481001
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2240
telemt_desync_full_logged_total 809
telemt_desync_suppressed_total 1431
telemt_desync_frames_bucket_total{bucket="1_2"} 450
telemt_desync_frames_bucket_total{bucket="3_10"} 777
telemt_desync_frames_bucket_total{bucket="gt_10"} 1013
telemt_pool_swap_total 35
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 3933
telemt_me_writer_restored_same_endpoint_total 3891
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 482435
telemt_user_connections_current{user="hello"} 869
telemt_user_octets_from_client{user="hello"} 30163358208 (28.09 GB)
telemt_user_octets_to_client{user="hello"} 168870492309 (157.27 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 338
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 48698.4 (13h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3049395
telemt_connections_bad_total 133715
telemt_connections_current 1598
telemt_connections_me_current 1598
telemt_handshake_timeouts_total 67285
telemt_upstream_connect_attempt_total 9620
telemt_upstream_connect_success_total 9456
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 9620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5457
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3941
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10031
telemt_me_reconnect_success_total 5787
telemt_me_reader_eof_total 6193
telemt_me_idle_close_by_peer_total 6193
telemt_me_route_drop_no_conn_total 1514107
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2610401
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11266
telemt_desync_full_logged_total 3717
telemt_desync_suppressed_total 7549
telemt_desync_frames_bucket_total{bucket="1_2"} 2152
telemt_desync_frames_bucket_total{bucket="3_10"} 4403
telemt_desync_frames_bucket_total{bucket="gt_10"} 4711
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 52
telemt_me_writer_removed_unexpected_total 5986
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 5732
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 2610174
telemt_user_connections_current{user="hello"} 1598
telemt_user_octets_from_client{user="hello"} 39852903954 (37.12 GB)
telemt_user_octets_to_client{user="hello"} 966199962598 (899.84 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 702
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 48676.4 (13h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2988625
telemt_connections_bad_total 477018
telemt_connections_current 1151
telemt_connections_me_current 1151
telemt_handshake_timeouts_total 44975
telemt_upstream_connect_attempt_total 7902
telemt_upstream_connect_success_total 7843
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 7901
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3841
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6337
telemt_me_reconnect_success_total 5403
telemt_me_reader_eof_total 5670
telemt_me_idle_close_by_peer_total 5669
telemt_me_route_drop_no_conn_total 1929949
telemt_me_route_drop_channel_closed_total 173
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2061733
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7745
telemt_desync_full_logged_total 2355
telemt_desync_suppressed_total 5390
telemt_desync_frames_bucket_total{bucket="1_2"} 1905
telemt_desync_frames_bucket_total{bucket="3_10"} 2946
telemt_desync_frames_bucket_total{bucket="gt_10"} 2894
telemt_pool_swap_total 47
telemt_me_writer_close_signal_drop_total 70
telemt_me_writer_removed_unexpected_total 5456
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5402
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 2057353
telemt_user_connections_current{user="hello"} 1151
telemt_user_octets_from_client{user="hello"} 30301589624 (28.22 GB)
telemt_user_octets_to_client{user="hello"} 792257049672 (737.85 GB)
telemt_user_unique_ips_current{user="hello"} 506
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 48664.3 (13h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2626675
telemt_connections_bad_total 158900
telemt_connections_current 1215
telemt_connections_me_current 1215
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 31572
telemt_upstream_connect_attempt_total 55767
telemt_upstream_connect_success_total 51477
telemt_upstream_connect_fail_total 4290
telemt_upstream_connect_attempts_per_request{bucket="1"} 55767
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7639
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 529
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4290
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 8652
telemt_me_reconnect_success_total 5808
telemt_me_reader_eof_total 6041
telemt_me_idle_close_by_peer_total 6040
telemt_me_route_drop_no_conn_total 1872062
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2164678
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8373
telemt_desync_full_logged_total 2650
telemt_desync_suppressed_total 5723
telemt_desync_frames_bucket_total{bucket="1_2"} 2063
telemt_desync_frames_bucket_total{bucket="3_10"} 3046
telemt_desync_frames_bucket_total{bucket="gt_10"} 3264
telemt_pool_swap_total 34
telemt_me_writer_close_signal_drop_total 478
telemt_me_writer_removed_unexpected_total 6438
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 5804
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 630
telemt_user_connections_total{user="hello"} 2206750
telemt_user_connections_current{user="hello"} 1215
telemt_user_octets_from_client{user="hello"} 35854237181 (33.39 GB)
telemt_user_octets_to_client{user="hello"} 621970318477 (579.25 GB)
telemt_user_msgs_from_client{user="hello"} 240837
telemt_user_msgs_to_client{user="hello"} 1741640
telemt_user_unique_ips_current{user="hello"} 449
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 102387.5 (28h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6311288
telemt_connections_bad_total 1047354
telemt_connections_current 1271
telemt_connections_me_current 1271
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 114250
telemt_upstream_connect_attempt_total 127871
telemt_upstream_connect_success_total 94584
telemt_upstream_connect_fail_total 33287
telemt_upstream_connect_attempts_per_request{bucket="1"} 127871
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12651
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1434
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33287
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 78842
telemt_me_reconnect_success_total 13171
telemt_me_reader_eof_total 14181
telemt_me_idle_close_by_peer_total 14167
telemt_me_route_drop_no_conn_total 2807945
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4478718
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
telemt_desync_total 19609
telemt_desync_full_logged_total 6215
telemt_desync_suppressed_total 13394
telemt_desync_frames_bucket_total{bucket="1_2"} 3455
telemt_desync_frames_bucket_total{bucket="3_10"} 8079
telemt_desync_frames_bucket_total{bucket="gt_10"} 8075
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 13480
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 13146
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 309
telemt_user_connections_total{user="hello"} 4553930
telemt_user_connections_current{user="hello"} 1271
telemt_user_octets_from_client{user="hello"} 72792072504 (67.79 GB)
telemt_user_octets_to_client{user="hello"} 1749832211088 (1.59 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 557
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 48627.4 (13h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 760728
telemt_connections_bad_total 78979
telemt_connections_current 463
telemt_connections_me_current 463
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13106
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
telemt_me_route_drop_no_conn_total 471937
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
telemt_desync_total 1397
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 874
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 576
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
telemt_user_connections_total{user="hello"} 618014
telemt_user_connections_current{user="hello"} 463
telemt_user_octets_from_client{user="hello"} 7455834895 (6.94 GB)
telemt_user_octets_to_client{user="hello"} 146474805062 (136.42 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 48628.8 (13h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2055415
telemt_connections_bad_total 120563
telemt_connections_current 1258
telemt_connections_me_current 1258
telemt_handshake_timeouts_total 38034
telemt_upstream_connect_attempt_total 8693
telemt_upstream_connect_success_total 8633
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 8693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4642
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3954
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6255
telemt_me_reconnect_success_total 6211
telemt_me_reader_eof_total 6555
telemt_me_idle_close_by_peer_total 6555
telemt_me_route_drop_no_conn_total 750237
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1761754
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9305
telemt_desync_full_logged_total 2994
telemt_desync_suppressed_total 6311
telemt_desync_frames_bucket_total{bucket="1_2"} 1766
telemt_desync_frames_bucket_total{bucket="3_10"} 3260
telemt_desync_frames_bucket_total{bucket="gt_10"} 4279
telemt_pool_swap_total 48
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 6303
telemt_me_writer_restored_same_endpoint_total 6194
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 1760862
telemt_user_connections_current{user="hello"} 1258
telemt_user_octets_from_client{user="hello"} 30092743936 (28.03 GB)
telemt_user_octets_to_client{user="hello"} 895160723680 (833.68 GB)
telemt_user_unique_ips_current{user="hello"} 512
telemt_user_unique_ips_recent_window{user="hello"} 95
```