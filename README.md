# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
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

# Server Metrics 2026-03-22 23:24:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 94665.2 (26h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3385554
telemt_connections_bad_total 273869
telemt_connections_current 829
telemt_connections_me_current 829
telemt_handshake_timeouts_total 106740
telemt_upstream_connect_attempt_total 34911
telemt_upstream_connect_success_total 34910
telemt_upstream_connect_attempts_per_request{bucket="1"} 34910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22725
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 1360
telemt_me_reconnect_success_total 568
telemt_me_reader_eof_total 584
telemt_me_idle_close_by_peer_total 584
telemt_me_route_drop_no_conn_total 2968927
telemt_me_route_drop_channel_closed_total 1230
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2821682
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 653
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 736
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 12052
telemt_desync_full_logged_total 3784
telemt_desync_suppressed_total 8268
telemt_desync_frames_bucket_total{bucket="1_2"} 3244
telemt_desync_frames_bucket_total{bucket="3_10"} 4402
telemt_desync_frames_bucket_total{bucket="gt_10"} 4406
telemt_pool_swap_total 105
telemt_pool_force_close_total 3227
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 637
telemt_me_draining_writers_reap_progress_total 31918
telemt_me_writer_removed_unexpected_total 564
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2323
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29827
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3171
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28691
telemt_me_writer_teardown_success_total{mode="normal"} 32150
telemt_me_writer_teardown_noop_total 31929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64079
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 373.905832
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64079
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 637
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 507
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2810971
telemt_user_connections_current{user="hello"} 829
telemt_user_octets_from_client{user="hello"} 40200314292 (37.44 GB)
telemt_user_octets_to_client{user="hello"} 764736825920 (712.22 GB)
telemt_user_unique_ips_current{user="hello"} 376
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 108031.1 (30h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3966408
telemt_connections_bad_total 360651
telemt_connections_current 439
telemt_connections_me_current 439
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100085
telemt_upstream_connect_attempt_total 66827
telemt_upstream_connect_success_total 66021
telemt_upstream_connect_fail_total 714
telemt_upstream_connect_attempts_per_request{bucket="1"} 66735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28782
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 714
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9585
telemt_me_reconnect_success_total 3503
telemt_me_reader_eof_total 3510
telemt_me_idle_close_by_peer_total 3510
telemt_me_route_drop_no_conn_total 3637341
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3154455
telemt_me_endpoint_quarantine_total 815
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 41
telemt_me_single_endpoint_outage_exit_total 41
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 837
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 2
telemt_desync_total 12875
telemt_desync_full_logged_total 7213
telemt_desync_suppressed_total 5662
telemt_desync_frames_bucket_total{bucket="1_2"} 2912
telemt_desync_frames_bucket_total{bucket="3_10"} 5053
telemt_desync_frames_bucket_total{bucket="gt_10"} 4910
telemt_pool_swap_total 99
telemt_pool_force_close_total 2959
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 243
telemt_me_draining_writers_reap_progress_total 43601
telemt_me_writer_removed_unexpected_total 3445
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5929
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41145
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2501
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40642
telemt_me_writer_teardown_success_total{mode="normal"} 47074
telemt_me_writer_teardown_noop_total 43602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90676
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.536983
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90676
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 243
telemt_me_refill_failed_total 230
telemt_me_writer_restored_same_endpoint_total 3155
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 262
telemt_user_connections_total{user="hello"} 3166953
telemt_user_connections_current{user="hello"} 439
telemt_user_octets_from_client{user="hello"} 42799785486 (39.86 GB)
telemt_user_octets_to_client{user="hello"} 782922271740 (729.15 GB)
telemt_user_msgs_from_client{user="hello"} 47428
telemt_user_msgs_to_client{user="hello"} 180951
telemt_user_unique_ips_current{user="hello"} 280
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 182890.9 (50h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16258217
telemt_connections_bad_total 1629843
telemt_connections_current 660
telemt_connections_me_current 660
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 396509
telemt_upstream_connect_attempt_total 81421
telemt_upstream_connect_success_total 81321
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 81338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39524
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1704
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2929
telemt_me_reconnect_success_total 1526
telemt_me_reader_eof_total 1471
telemt_me_idle_close_by_peer_total 1469
telemt_me_route_drop_no_conn_total 14035799
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12919086
telemt_me_endpoint_quarantine_total 1192
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1369
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 53382
telemt_desync_full_logged_total 16940
telemt_desync_suppressed_total 36442
telemt_desync_frames_bucket_total{bucket="1_2"} 11865
telemt_desync_frames_bucket_total{bucket="3_10"} 20791
telemt_desync_frames_bucket_total{bucket="gt_10"} 20726
telemt_pool_swap_total 198
telemt_pool_force_close_total 6579
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1051
telemt_me_draining_writers_reap_progress_total 61117
telemt_me_writer_removed_unexpected_total 1418
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5293
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56514
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6109
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54538
telemt_me_writer_teardown_success_total{mode="normal"} 61807
telemt_me_writer_teardown_noop_total 61170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 111922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 115486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 117258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 119649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 121316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 122367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 122938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 122968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 122969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 122973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 122975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 122977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 122977
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.413907
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 122977
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1051
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 1319
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 12919295
telemt_user_connections_current{user="hello"} 660
telemt_user_octets_from_client{user="hello"} 190554544861 (177.47 GB)
telemt_user_octets_to_client{user="hello"} 3474599303999 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 296
telemt_user_unique_ips_recent_window{user="hello"} 299
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 182892.3 (50h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11800829
telemt_connections_bad_total 1217432
telemt_connections_current 454
telemt_connections_me_current 454
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344211
telemt_upstream_connect_attempt_total 95899
telemt_upstream_connect_success_total 94586
telemt_upstream_connect_fail_total 865
telemt_upstream_connect_attempts_per_request{bucket="1"} 95451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51153
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39448
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3797
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 865
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4344
telemt_me_reconnect_success_total 1833
telemt_me_reader_eof_total 1696
telemt_me_idle_close_by_peer_total 1696
telemt_me_route_drop_no_conn_total 4547818
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8770556
telemt_me_endpoint_quarantine_total 1200
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1391
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 38629
telemt_desync_full_logged_total 13001
telemt_desync_suppressed_total 25628
telemt_desync_frames_bucket_total{bucket="1_2"} 9553
telemt_desync_frames_bucket_total{bucket="3_10"} 14844
telemt_desync_frames_bucket_total{bucket="gt_10"} 14232
telemt_pool_swap_total 195
telemt_pool_force_close_total 5940
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 706
telemt_me_draining_writers_reap_progress_total 59476
telemt_me_writer_removed_unexpected_total 1729
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5412
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55646
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5428
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53536
telemt_me_writer_teardown_success_total{mode="normal"} 61058
telemt_me_writer_teardown_noop_total 59501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 113841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 117039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 118184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 119375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 120134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 120474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 120549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 120551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 120557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 120559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 120559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 120559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 120559
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.283771
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 120559
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 1564
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 8708359
telemt_user_connections_current{user="hello"} 454
telemt_user_octets_from_client{user="hello"} 217477285308 (202.54 GB)
telemt_user_octets_to_client{user="hello"} 3943830237555 (3.59 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 182856.4 (50h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10997503
telemt_connections_bad_total 962465
telemt_connections_current 642
telemt_connections_me_current 642
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345126
telemt_upstream_connect_attempt_total 80027
telemt_upstream_connect_success_total 78475
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 78680
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37870
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2012
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2358
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5667
telemt_me_reconnect_success_total 2314
telemt_me_reader_eof_total 2054
telemt_me_idle_close_by_peer_total 2053
telemt_me_route_drop_no_conn_total 5329808
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8319363
telemt_me_endpoint_quarantine_total 1279
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1345
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 37926
telemt_desync_full_logged_total 12575
telemt_desync_suppressed_total 25351
telemt_desync_frames_bucket_total{bucket="1_2"} 9579
telemt_desync_frames_bucket_total{bucket="3_10"} 14504
telemt_desync_frames_bucket_total{bucket="gt_10"} 13843
telemt_pool_swap_total 191
telemt_pool_force_close_total 5827
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 736
telemt_me_draining_writers_reap_progress_total 59689
telemt_me_writer_removed_unexpected_total 2208
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6135
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55690
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5256
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53862
telemt_me_writer_teardown_success_total{mode="normal"} 61825
telemt_me_writer_teardown_noop_total 59760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 115767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 118478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 119430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 120503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 121104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 121318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 121446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 121477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 121485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 121498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 121531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 121534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 121585
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.652665
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 121585
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 736
telemt_me_refill_failed_total 178
telemt_me_writer_restored_same_endpoint_total 2005
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 8311357
telemt_user_connections_current{user="hello"} 642
telemt_user_octets_from_client{user="hello"} 192338741851 (179.13 GB)
telemt_user_octets_to_client{user="hello"} 3457524321141 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 284
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 53136.5 (14h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11143262
telemt_connections_bad_total 667704
telemt_connections_current 1018
telemt_connections_me_current 1018
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 259546
telemt_upstream_connect_attempt_total 54269
telemt_upstream_connect_success_total 51467
telemt_upstream_connect_fail_total 1893
telemt_upstream_connect_attempts_per_request{bucket="1"} 53360
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17319
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6001
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1893
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7362
telemt_me_reconnect_success_total 1130
telemt_me_reader_eof_total 702
telemt_me_idle_close_by_peer_total 701
telemt_me_route_drop_no_conn_total 25273813
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9255565
telemt_me_endpoint_quarantine_total 375
telemt_me_single_endpoint_outage_enter_total 84
telemt_me_single_endpoint_outage_exit_total 84
telemt_me_single_endpoint_outage_reconnect_attempt_total 157
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 157
telemt_me_single_endpoint_shadow_rotate_total 420
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 8
telemt_desync_total 16051
telemt_desync_full_logged_total 4312
telemt_desync_suppressed_total 11739
telemt_desync_frames_bucket_total{bucket="1_2"} 3059
telemt_desync_frames_bucket_total{bucket="3_10"} 6493
telemt_desync_frames_bucket_total{bucket="gt_10"} 6499
telemt_pool_swap_total 54
telemt_pool_force_close_total 1836
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 467
telemt_me_draining_writers_reap_progress_total 16056
telemt_me_writer_removed_unexpected_total 1020
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2253
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14775
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1529
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14220
telemt_me_writer_teardown_success_total{mode="normal"} 17028
telemt_me_writer_teardown_noop_total 16075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33103
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.246554
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33103
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 467
telemt_me_refill_failed_total 332
telemt_me_writer_restored_same_endpoint_total 731
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 281
telemt_user_connections_total{user="hello"} 9281065
telemt_user_connections_current{user="hello"} 1018
telemt_user_octets_from_client{user="hello"} 86331290646 (80.40 GB)
telemt_user_octets_to_client{user="hello"} 584592828285 (544.44 GB)
telemt_user_msgs_from_client{user="hello"} 67224
telemt_user_msgs_to_client{user="hello"} 56168
telemt_user_unique_ips_current{user="hello"} 426
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 182863.1 (50h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10934125
telemt_connections_bad_total 939898
telemt_connections_current 743
telemt_connections_me_current 743
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 241515
telemt_upstream_connect_attempt_total 108818
telemt_upstream_connect_success_total 107688
telemt_upstream_connect_fail_total 958
telemt_upstream_connect_attempts_per_request{bucket="1"} 108646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64718
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41376
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1356
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 958
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72783
telemt_me_reconnect_success_total 2995
telemt_me_reader_eof_total 2687
telemt_me_idle_close_by_peer_total 2685
telemt_me_route_drop_no_conn_total 5250967
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8627829
telemt_me_endpoint_quarantine_total 1219
telemt_me_single_endpoint_outage_enter_total 41
telemt_me_single_endpoint_outage_exit_total 41
telemt_me_single_endpoint_outage_reconnect_attempt_total 43
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 43
telemt_me_single_endpoint_shadow_rotate_total 1374
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 46044
telemt_desync_full_logged_total 15759
telemt_desync_suppressed_total 30285
telemt_desync_frames_bucket_total{bucket="1_2"} 9346
telemt_desync_frames_bucket_total{bucket="3_10"} 17624
telemt_desync_frames_bucket_total{bucket="gt_10"} 19074
telemt_pool_swap_total 187
telemt_pool_force_close_total 5522
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 658
telemt_me_draining_writers_reap_progress_total 63763
telemt_me_writer_removed_unexpected_total 2718
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6635
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59879
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4773
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58241
telemt_me_writer_teardown_success_total{mode="normal"} 66514
telemt_me_writer_teardown_noop_total 63764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 128144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 129542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 129961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 130234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 130268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 130271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 130271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 130274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 130278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 130278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 130278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 130278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 130278
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.197690
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 130278
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 658
telemt_me_refill_failed_total 4297
telemt_me_writer_restored_same_endpoint_total 2526
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8630893
telemt_user_connections_current{user="hello"} 743
telemt_user_octets_from_client{user="hello"} 194130779713 (180.80 GB)
telemt_user_octets_to_client{user="hello"} 3295191149376 (3.00 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 350
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 119699.3 (33h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11614325
telemt_connections_bad_total 471743
telemt_connections_current 573
telemt_connections_me_current 573
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4751139
telemt_upstream_connect_attempt_total 56994
telemt_upstream_connect_success_total 56577
telemt_upstream_connect_fail_total 406
telemt_upstream_connect_attempts_per_request{bucket="1"} 56983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25825
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 406
telemt_me_reconnect_attempts_total 48743
telemt_me_reconnect_success_total 1757
telemt_me_reader_eof_total 1422
telemt_me_idle_close_by_peer_total 1421
telemt_me_route_drop_no_conn_total 4078912
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5581991
telemt_me_endpoint_quarantine_total 784
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 910
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31357
telemt_desync_full_logged_total 10688
telemt_desync_suppressed_total 20669
telemt_desync_frames_bucket_total{bucket="1_2"} 6227
telemt_desync_frames_bucket_total{bucket="3_10"} 12370
telemt_desync_frames_bucket_total{bucket="gt_10"} 12760
telemt_pool_swap_total 126
telemt_pool_force_close_total 3764
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 372
telemt_me_draining_writers_reap_progress_total 42862
telemt_me_writer_removed_unexpected_total 1475
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3616
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40762
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3323
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39098
telemt_me_writer_teardown_success_total{mode="normal"} 44378
telemt_me_writer_teardown_noop_total 42869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87247
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.644788
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87247
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 372
telemt_me_refill_failed_total 2730
telemt_me_writer_restored_same_endpoint_total 1561
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5574593
telemt_user_connections_current{user="hello"} 573
telemt_user_octets_from_client{user="hello"} 118782767584 (110.63 GB)
telemt_user_octets_to_client{user="hello"} 2156854921650 (1.96 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 277
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 100670.0 (27h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1484402
telemt_connections_bad_total 36464
telemt_connections_current 471
telemt_connections_me_current 471
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 29581
telemt_upstream_connect_attempt_total 47038
telemt_upstream_connect_success_total 46889
telemt_upstream_connect_fail_total 121
telemt_upstream_connect_attempts_per_request{bucket="1"} 47010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24816
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 778
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 121
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2157
telemt_me_reconnect_success_total 875
telemt_me_reader_eof_total 855
telemt_me_idle_close_by_peer_total 855
telemt_me_route_drop_no_conn_total 510255
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1318111
telemt_me_endpoint_quarantine_total 813
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 829
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 8413
telemt_desync_full_logged_total 2522
telemt_desync_suppressed_total 5891
telemt_desync_frames_bucket_total{bucket="1_2"} 2168
telemt_desync_frames_bucket_total{bucket="3_10"} 3247
telemt_desync_frames_bucket_total{bucket="gt_10"} 2998
telemt_pool_swap_total 108
telemt_pool_force_close_total 2806
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 156
telemt_me_draining_writers_reap_progress_total 39522
telemt_me_writer_removed_unexpected_total 827
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3095
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37289
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2718
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36716
telemt_me_writer_teardown_success_total{mode="normal"} 40384
telemt_me_writer_teardown_noop_total 39526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79910
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.069845
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79910
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 156
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 742
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 1313979
telemt_user_connections_current{user="hello"} 471
telemt_user_octets_from_client{user="hello"} 25668386481 (23.91 GB)
telemt_user_octets_to_client{user="hello"} 563967986175 (525.24 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 182867.6 (50h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13248705
telemt_connections_bad_total 1574372
telemt_connections_current 771
telemt_connections_me_current 771
telemt_handshake_timeouts_total 382402
telemt_upstream_connect_attempt_total 70617
telemt_upstream_connect_success_total 70274
telemt_upstream_connect_fail_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 70481
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35345
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 207
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2802
telemt_me_reconnect_success_total 1425
telemt_me_reader_eof_total 1405
telemt_me_idle_close_by_peer_total 1405
telemt_me_route_drop_no_conn_total 4476415
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10009556
telemt_me_endpoint_quarantine_total 1269
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1377
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 41833
telemt_desync_full_logged_total 13657
telemt_desync_suppressed_total 28176
telemt_desync_frames_bucket_total{bucket="1_2"} 10062
telemt_desync_frames_bucket_total{bucket="3_10"} 15382
telemt_desync_frames_bucket_total{bucket="gt_10"} 16389
telemt_pool_swap_total 203
telemt_pool_force_close_total 5475
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 669
telemt_me_draining_writers_reap_progress_total 63721
telemt_me_writer_removed_unexpected_total 1347
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5104
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60012
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5301
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58246
telemt_me_writer_teardown_success_total{mode="normal"} 65116
telemt_me_writer_teardown_noop_total 63723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 126248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 127947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 128330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 128706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 128826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 128839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 128839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 128839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 128839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 128839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 128839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 128839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 128839
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.695821
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 128839
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 669
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1250
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 9976305
telemt_user_connections_current{user="hello"} 771
telemt_user_octets_from_client{user="hello"} 194364342700 (181.02 GB)
telemt_user_octets_to_client{user="hello"} 4426299830176 (4.03 TB)
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 182864.3 (50h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11543516
telemt_connections_bad_total 1322168
telemt_connections_current 552
telemt_connections_me_current 552
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 306961
telemt_upstream_connect_attempt_total 97226
telemt_upstream_connect_success_total 96359
telemt_upstream_connect_fail_total 659
telemt_upstream_connect_attempts_per_request{bucket="1"} 97018
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40930
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 659
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10219
telemt_me_reconnect_success_total 2505
telemt_me_reader_eof_total 2326
telemt_me_idle_close_by_peer_total 2325
telemt_me_seq_mismatch_total 90
telemt_me_route_drop_no_conn_total 5636916
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8913421
telemt_me_endpoint_quarantine_total 1446
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 50
telemt_me_single_endpoint_outage_exit_total 50
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 48
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 1377
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 48
telemt_desync_total 41544
telemt_desync_full_logged_total 13344
telemt_desync_suppressed_total 28200
telemt_desync_frames_bucket_total{bucket="1_2"} 10703
telemt_desync_frames_bucket_total{bucket="3_10"} 15277
telemt_desync_frames_bucket_total{bucket="gt_10"} 15564
telemt_pool_swap_total 193
telemt_pool_force_close_total 5267
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 655
telemt_me_draining_writers_reap_progress_total 63630
telemt_me_writer_removed_unexpected_total 2363
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6459
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59616
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4796
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58363
telemt_me_writer_teardown_success_total{mode="normal"} 66075
telemt_me_writer_teardown_noop_total 63635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 127031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 128805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 129341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 129660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 129710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 129710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 129710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 129710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 129710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 129710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 129710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 129710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 129710
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.369084
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 129710
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 655
telemt_me_refill_failed_total 399
telemt_me_writer_restored_same_endpoint_total 2025
telemt_me_writer_restored_fallback_total 124
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 8918781
telemt_user_connections_current{user="hello"} 552
telemt_user_octets_from_client{user="hello"} 157023102685 (146.24 GB)
telemt_user_octets_to_client{user="hello"} 3471058230599 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 278
telemt_user_unique_ips_recent_window{user="hello"} 59
```