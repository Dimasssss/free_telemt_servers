# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

**Принимаю донаты криптой для добавления и продления серверов:**  
- TON: UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB

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
Этот сервер пользуется большим спросом. Я арендовал еще один такой же, чтобы распределить нагрузку.

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

# Server Metrics 2026-03-20 16:09:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 6821.0 (1h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 351713
telemt_connections_bad_total 15177
telemt_connections_current 1690
telemt_connections_me_current 1690
telemt_handshake_timeouts_total 6794
telemt_upstream_connect_attempt_total 2687
telemt_upstream_connect_success_total 2675
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1008
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1659
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 504
telemt_me_reconnect_success_total 202
telemt_me_reader_eof_total 213
telemt_me_idle_close_by_peer_total 213
telemt_me_route_drop_no_conn_total 476798
telemt_me_route_drop_channel_closed_total 155
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 311646
telemt_me_endpoint_quarantine_total 42
telemt_me_single_endpoint_shadow_rotate_total 52
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_desync_total 1051
telemt_desync_full_logged_total 331
telemt_desync_suppressed_total 720
telemt_desync_frames_bucket_total{bucket="1_2"} 215
telemt_desync_frames_bucket_total{bucket="3_10"} 450
telemt_desync_frames_bucket_total{bucket="gt_10"} 386
telemt_pool_swap_total 5
telemt_pool_force_close_total 195
telemt_me_writer_close_signal_drop_total 77
telemt_me_draining_writers_reap_progress_total 2241
telemt_me_writer_removed_unexpected_total 213
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 346
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2097
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 144
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2046
telemt_me_writer_teardown_success_total{mode="normal"} 2443
telemt_me_writer_teardown_noop_total 2242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4685
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 32.465376
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4685
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 77
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 195
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 311041
telemt_user_connections_current{user="hello"} 1690
telemt_user_octets_from_client{user="hello"} 2898053664 (2.70 GB)
telemt_user_octets_to_client{user="hello"} 56807145220 (52.91 GB)
telemt_user_unique_ips_current{user="hello"} 593
telemt_user_unique_ips_recent_window{user="hello"} 215
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 6830.5 (1h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 844970
telemt_connections_bad_total 46135
telemt_connections_current 4190
telemt_connections_me_current 4190
telemt_handshake_timeouts_total 13171
telemt_upstream_connect_attempt_total 2254
telemt_upstream_connect_success_total 2232
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 2254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 153
telemt_me_reconnect_success_total 90
telemt_me_reader_eof_total 75
telemt_me_idle_close_by_peer_total 75
telemt_me_route_drop_no_conn_total 340602
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 640442
telemt_me_endpoint_quarantine_total 31
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 52
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_desync_total 2180
telemt_desync_full_logged_total 746
telemt_desync_suppressed_total 1434
telemt_desync_frames_bucket_total{bucket="1_2"} 463
telemt_desync_frames_bucket_total{bucket="3_10"} 875
telemt_desync_frames_bucket_total{bucket="gt_10"} 842
telemt_pool_swap_total 6
telemt_pool_force_close_total 265
telemt_me_writer_close_signal_drop_total 40
telemt_me_draining_writers_reap_progress_total 1936
telemt_me_writer_removed_unexpected_total 75
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 216
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1767
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 204
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 61
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1671
telemt_me_writer_teardown_success_total{mode="normal"} 1983
telemt_me_writer_teardown_noop_total 1942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3925
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.879572
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3925
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 40
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 81
telemt_me_writer_restored_fallback_total 1
telemt_me_no_writer_failfast_total 41
telemt_me_async_recovery_trigger_total 396
telemt_user_connections_total{user="hello"} 639769
telemt_user_connections_current{user="hello"} 4190
telemt_user_octets_from_client{user="hello"} 7843318736 (7.30 GB)
telemt_user_octets_to_client{user="hello"} 190950351224 (177.84 GB)
telemt_user_unique_ips_current{user="hello"} 1385
telemt_user_unique_ips_recent_window{user="hello"} 633
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 6824.9 (1h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 608694
telemt_connections_bad_total 38859
telemt_connections_current 4368
telemt_connections_me_current 4368
telemt_handshake_timeouts_total 9113
telemt_upstream_connect_attempt_total 2913
telemt_upstream_connect_success_total 2845
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 2910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1498
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_reconnect_attempts_total 343
telemt_me_reconnect_success_total 229
telemt_me_reader_eof_total 193
telemt_me_idle_close_by_peer_total 193
telemt_me_route_drop_no_conn_total 246171
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 512755
telemt_me_endpoint_quarantine_total 44
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 50
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_me_writers_active_current 93
telemt_desync_total 1703
telemt_desync_full_logged_total 566
telemt_desync_suppressed_total 1137
telemt_desync_frames_bucket_total{bucket="1_2"} 326
telemt_desync_frames_bucket_total{bucket="3_10"} 701
telemt_desync_frames_bucket_total{bucket="gt_10"} 676
telemt_pool_swap_total 4
telemt_pool_force_close_total 236
telemt_pool_stale_pick_total 1363
telemt_me_writer_close_signal_drop_total 39
telemt_me_draining_writers_reap_progress_total 2402
telemt_me_writer_removed_unexpected_total 190
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 349
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2208
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 119
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 117
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2166
telemt_me_writer_teardown_success_total{mode="normal"} 2557
telemt_me_writer_teardown_noop_total 2402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4959
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.663824
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4959
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 39
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 215
telemt_me_async_recovery_trigger_total 48
telemt_user_connections_total{user="hello"} 512355
telemt_user_connections_current{user="hello"} 4368
telemt_user_octets_from_client{user="hello"} 8929507408 (8.32 GB)
telemt_user_octets_to_client{user="hello"} 180476989192 (168.08 GB)
telemt_user_unique_ips_current{user="hello"} 1675
telemt_user_unique_ips_recent_window{user="hello"} 544
```

## koara.io

```
telemt 3.3.27

telemt_uptime_seconds 20883.5 (5h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3659773
telemt_connections_bad_total 371554
telemt_connections_current 5824
telemt_connections_me_current 5824
telemt_handshake_timeouts_total 66779
telemt_upstream_connect_attempt_total 6805
telemt_upstream_connect_success_total 6765
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 6794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3664
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 659
telemt_me_reconnect_success_total 419
telemt_me_reader_eof_total 426
telemt_me_idle_close_by_peer_total 426
telemt_me_route_drop_no_conn_total 2367878
telemt_me_route_drop_channel_closed_total 152
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2906881
telemt_me_writer_pick_total{mode="p2c",result="full"} 1
telemt_me_endpoint_quarantine_total 88
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 134
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_desync_total 7905
telemt_desync_full_logged_total 2260
telemt_desync_suppressed_total 5645
telemt_desync_frames_bucket_total{bucket="1_2"} 1983
telemt_desync_frames_bucket_total{bucket="3_10"} 3070
telemt_desync_frames_bucket_total{bucket="gt_10"} 2852
telemt_pool_swap_total 16
telemt_pool_force_close_total 802
telemt_me_writer_close_signal_drop_total 198
telemt_me_draining_writers_reap_progress_total 5812
telemt_me_writer_removed_unexpected_total 422
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 795
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5362
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 463
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 339
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5010
telemt_me_writer_teardown_success_total{mode="normal"} 6157
telemt_me_writer_teardown_noop_total 5822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 9592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 10583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 10882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 11232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 11589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 11857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 11974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 11979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 11979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 11979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 11979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 11979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 11979
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 59.269902
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 11979
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 198
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 402
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 2903617
telemt_user_connections_current{user="hello"} 5824
telemt_user_octets_from_client{user="hello"} 32024781144 (29.83 GB)
telemt_user_octets_to_client{user="hello"} 782265725544 (728.54 GB)
telemt_user_unique_ips_current{user="hello"} 1821
telemt_user_unique_ips_recent_window{user="hello"} 724
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 6826.4 (1h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2565628
telemt_connections_bad_total 58289
telemt_connections_current 2934
telemt_connections_direct_current 1192
telemt_connections_me_current 1742
telemt_handshake_timeouts_total 29162
telemt_upstream_connect_attempt_total 11065
telemt_upstream_connect_success_total 10482
telemt_upstream_connect_fail_total 366
telemt_upstream_connect_attempts_per_request{bucket="1"} 10848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2505
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 250
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 366
telemt_me_keepalive_timeout_total 185
telemt_me_reconnect_attempts_total 568
telemt_me_reconnect_success_total 280
telemt_me_reader_eof_total 235
telemt_me_idle_close_by_peer_total 235
telemt_me_route_drop_no_conn_total 5226071
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2319591
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 53
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_desync_total 2991
telemt_desync_full_logged_total 848
telemt_desync_suppressed_total 2143
telemt_desync_frames_bucket_total{bucket="1_2"} 632
telemt_desync_frames_bucket_total{bucket="3_10"} 1341
telemt_desync_frames_bucket_total{bucket="gt_10"} 1018
telemt_pool_swap_total 4
telemt_pool_force_close_total 183
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 89
telemt_me_draining_writers_reap_progress_total 1953
telemt_me_writer_removed_unexpected_total 363
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 497
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1817
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 120
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 63
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1770
telemt_me_writer_teardown_success_total{mode="normal"} 2314
telemt_me_writer_teardown_noop_total 1954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4268
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.587342
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4268
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 89
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 240
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 2328157
telemt_user_connections_current{user="hello"} 2934
telemt_user_octets_from_client{user="hello"} 9946270099 (9.26 GB)
telemt_user_octets_to_client{user="hello"} 73443433792 (68.40 GB)
telemt_user_msgs_from_client{user="hello"} 8736
telemt_user_msgs_to_client{user="hello"} 7574
telemt_user_unique_ips_current{user="hello"} 1029
telemt_user_unique_ips_recent_window{user="hello"} 1065
```

## rdp-onedash.ru

```
telemt 3.3.28

telemt_uptime_seconds 6828.1 (1h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2259150
telemt_connections_bad_total 156778
telemt_connections_current 6703
telemt_connections_me_current 6703
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 20435
telemt_upstream_connect_attempt_total 19115
telemt_upstream_connect_success_total 19108
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 19115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12755
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5517
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 113
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 723
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 195
telemt_me_reconnect_success_total 59
telemt_me_reader_eof_total 58
telemt_me_idle_close_by_peer_total 58
telemt_me_route_drop_no_conn_total 3850727
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1914661
telemt_me_endpoint_quarantine_total 38
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 49
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_desync_total 3089
telemt_desync_full_logged_total 906
telemt_desync_suppressed_total 2183
telemt_desync_frames_bucket_total{bucket="1_2"} 789
telemt_desync_frames_bucket_total{bucket="3_10"} 1338
telemt_desync_frames_bucket_total{bucket="gt_10"} 962
telemt_pool_swap_total 7
telemt_pool_force_close_total 211
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 74
telemt_me_draining_writers_reap_progress_total 1553
telemt_me_writer_removed_unexpected_total 56
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 183
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1395
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 183
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 28
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1342
telemt_me_writer_teardown_success_total{mode="normal"} 1578
telemt_me_writer_teardown_noop_total 1557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3135
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 114.093168
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3135
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 74
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 1928337
telemt_user_connections_current{user="hello"} 6703
telemt_user_octets_from_client{user="hello"} 14623029856 (13.62 GB)
telemt_user_octets_to_client{user="hello"} 139736149935 (130.14 GB)
telemt_user_msgs_from_client{user="hello"} 75809
telemt_user_msgs_to_client{user="hello"} 92195
telemt_user_unique_ips_current{user="hello"} 2005
telemt_user_unique_ips_recent_window{user="hello"} 1127
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 6255.9 (1h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125777
telemt_connections_bad_total 1313
telemt_connections_current 726
telemt_connections_me_current 726
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 2249
telemt_upstream_connect_attempt_total 3943
telemt_upstream_connect_success_total 3940
telemt_upstream_connect_attempts_per_request{bucket="1"} 3940
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2808
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 116
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 212
telemt_me_reconnect_success_total 53
telemt_me_reader_eof_total 49
telemt_me_idle_close_by_peer_total 49
telemt_me_route_drop_no_conn_total 102315
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111302
telemt_me_endpoint_quarantine_total 42
telemt_me_single_endpoint_shadow_rotate_total 47
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 1
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
telemt_desync_total 344
telemt_desync_full_logged_total 120
telemt_desync_suppressed_total 224
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 131
telemt_desync_frames_bucket_total{bucket="gt_10"} 154
telemt_pool_swap_total 6
telemt_pool_force_close_total 165
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 45
telemt_me_draining_writers_reap_progress_total 1947
telemt_me_writer_removed_unexpected_total 49
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 203
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1778
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 164
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1782
telemt_me_writer_teardown_success_total{mode="normal"} 1981
telemt_me_writer_teardown_noop_total 1948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3929
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.366510
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3929
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 45
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 39
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 112313
telemt_user_connections_current{user="hello"} 726
telemt_user_octets_from_client{user="hello"} 1214144566 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 21485306325 (20.01 GB)
telemt_user_msgs_from_client{user="hello"} 5317
telemt_user_msgs_to_client{user="hello"} 6420
telemt_user_unique_ips_current{user="hello"} 272
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## 4vps.su

```
telemt 3.3.28

telemt_uptime_seconds 6826.3 (1h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1193514
telemt_connections_bad_total 75357
telemt_connections_current 7598
telemt_connections_me_current 7598
telemt_handshake_timeouts_total 41017
telemt_upstream_connect_attempt_total 2037
telemt_upstream_connect_success_total 2035
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2036
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1092
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 127
telemt_me_reconnect_success_total 70
telemt_me_reader_eof_total 72
telemt_me_idle_close_by_peer_total 72
telemt_me_route_drop_no_conn_total 558066
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1009984
telemt_me_endpoint_quarantine_total 30
telemt_me_single_endpoint_shadow_rotate_total 45
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_desync_total 3715
telemt_desync_full_logged_total 1039
telemt_desync_suppressed_total 2676
telemt_desync_frames_bucket_total{bucket="1_2"} 950
telemt_desync_frames_bucket_total{bucket="3_10"} 1382
telemt_desync_frames_bucket_total{bucket="gt_10"} 1383
telemt_pool_swap_total 6
telemt_pool_force_close_total 229
telemt_me_writer_close_signal_drop_total 27
telemt_me_draining_writers_reap_progress_total 1716
telemt_me_writer_removed_unexpected_total 71
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 190
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1600
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 183
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1487
telemt_me_writer_teardown_success_total{mode="normal"} 1790
telemt_me_writer_teardown_noop_total 1717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3507
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.021864
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3507
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 27
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 63
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 1008965
telemt_user_connections_current{user="hello"} 7598
telemt_user_octets_from_client{user="hello"} 13473476704 (12.55 GB)
telemt_user_octets_to_client{user="hello"} 317951547752 (296.12 GB)
telemt_user_unique_ips_current{user="hello"} 2253
telemt_user_unique_ips_recent_window{user="hello"} 931
```