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

# Server Metrics 2026-03-20 15:45:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 5372.0 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 267002
telemt_connections_bad_total 11625
telemt_connections_current 1575
telemt_connections_me_current 1575
telemt_handshake_timeouts_total 5965
telemt_upstream_connect_attempt_total 2212
telemt_upstream_connect_success_total 2203
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1357
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 465
telemt_me_reconnect_success_total 196
telemt_me_reader_eof_total 206
telemt_me_idle_close_by_peer_total 206
telemt_me_route_drop_no_conn_total 303229
telemt_me_route_drop_channel_closed_total 109
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 235103
telemt_me_endpoint_quarantine_total 32
telemt_me_single_endpoint_shadow_rotate_total 38
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 886
telemt_desync_full_logged_total 273
telemt_desync_suppressed_total 613
telemt_desync_frames_bucket_total{bucket="1_2"} 163
telemt_desync_frames_bucket_total{bucket="3_10"} 400
telemt_desync_frames_bucket_total{bucket="gt_10"} 323
telemt_pool_swap_total 3
telemt_pool_force_close_total 136
telemt_me_writer_close_signal_drop_total 54
telemt_me_draining_writers_reap_progress_total 1802
telemt_me_writer_removed_unexpected_total 205
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1695
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 86
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 50
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1666
telemt_me_writer_teardown_success_total{mode="normal"} 2002
telemt_me_writer_teardown_noop_total 1802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3804
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.982403
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3804
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 54
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 189
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 234905
telemt_user_connections_current{user="hello"} 1575
telemt_user_octets_from_client{user="hello"} 2419950492 (2.25 GB)
telemt_user_octets_to_client{user="hello"} 42975716532 (40.02 GB)
telemt_user_unique_ips_current{user="hello"} 578
telemt_user_unique_ips_recent_window{user="hello"} 228
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 5381.6 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 671966
telemt_connections_bad_total 40988
telemt_connections_current 4525
telemt_connections_me_current 4525
telemt_handshake_timeouts_total 9761
telemt_upstream_connect_attempt_total 1810
telemt_upstream_connect_success_total 1789
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 1810
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 987
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 147
telemt_me_reconnect_success_total 85
telemt_me_reader_eof_total 70
telemt_me_idle_close_by_peer_total 70
telemt_me_route_drop_no_conn_total 247714
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 500051
telemt_me_endpoint_quarantine_total 19
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 40
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
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
telemt_me_writers_active_current 86
telemt_desync_total 1628
telemt_desync_full_logged_total 576
telemt_desync_suppressed_total 1052
telemt_desync_frames_bucket_total{bucket="1_2"} 347
telemt_desync_frames_bucket_total{bucket="3_10"} 630
telemt_desync_frames_bucket_total{bucket="gt_10"} 651
telemt_pool_swap_total 4
telemt_pool_force_close_total 168
telemt_me_writer_close_signal_drop_total 28
telemt_me_draining_writers_reap_progress_total 1484
telemt_me_writer_removed_unexpected_total 70
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 163
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1364
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 149
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 19
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1316
telemt_me_writer_teardown_success_total{mode="normal"} 1527
telemt_me_writer_teardown_noop_total 1490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3017
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.739425
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3017
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 28
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 76
telemt_me_writer_restored_fallback_total 1
telemt_me_no_writer_failfast_total 41
telemt_me_async_recovery_trigger_total 396
telemt_user_connections_total{user="hello"} 499733
telemt_user_connections_current{user="hello"} 4525
telemt_user_octets_from_client{user="hello"} 6137420832 (5.72 GB)
telemt_user_octets_to_client{user="hello"} 147658968688 (137.52 GB)
telemt_user_unique_ips_current{user="hello"} 1601
telemt_user_unique_ips_recent_window{user="hello"} 578
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 5375.6 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 465070
telemt_connections_bad_total 30462
telemt_connections_current 3645
telemt_connections_me_current 3645
telemt_handshake_timeouts_total 5825
telemt_upstream_connect_attempt_total 2237
telemt_upstream_connect_success_total 2187
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 2234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1158
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_reconnect_attempts_total 256
telemt_me_reconnect_success_total 161
telemt_me_reader_eof_total 138
telemt_me_idle_close_by_peer_total 138
telemt_me_route_drop_no_conn_total 185153
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 400033
telemt_me_endpoint_quarantine_total 29
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 39
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
telemt_me_writers_active_current 89
telemt_desync_total 1172
telemt_desync_full_logged_total 413
telemt_desync_suppressed_total 759
telemt_desync_frames_bucket_total{bucket="1_2"} 222
telemt_desync_frames_bucket_total{bucket="3_10"} 451
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 3
telemt_pool_force_close_total 168
telemt_pool_stale_pick_total 1363
telemt_me_writer_close_signal_drop_total 31
telemt_me_draining_writers_reap_progress_total 1814
telemt_me_writer_removed_unexpected_total 135
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 245
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1680
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 99
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 69
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1646
telemt_me_writer_teardown_success_total{mode="normal"} 1925
telemt_me_writer_teardown_noop_total 1814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3739
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.168266
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3739
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 31
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 151
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 399845
telemt_user_connections_current{user="hello"} 3645
telemt_user_octets_from_client{user="hello"} 7283627356 (6.78 GB)
telemt_user_octets_to_client{user="hello"} 138331168044 (128.83 GB)
telemt_user_unique_ips_current{user="hello"} 1386
telemt_user_unique_ips_recent_window{user="hello"} 502
```

## koara.io

```
telemt 3.3.27

telemt_uptime_seconds 19434.1 (5h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3449786
telemt_connections_bad_total 343740
telemt_connections_current 5514
telemt_connections_me_current 5514
telemt_handshake_timeouts_total 62947
telemt_upstream_connect_attempt_total 6413
telemt_upstream_connect_success_total 6376
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 6402
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2820
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3458
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 651
telemt_me_reconnect_success_total 410
telemt_me_reader_eof_total 418
telemt_me_idle_close_by_peer_total 418
telemt_me_route_drop_no_conn_total 2288497
telemt_me_route_drop_channel_closed_total 140
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2745681
telemt_me_writer_pick_total{mode="p2c",result="full"} 1
telemt_me_endpoint_quarantine_total 85
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 124
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
telemt_desync_total 7317
telemt_desync_full_logged_total 2088
telemt_desync_suppressed_total 5229
telemt_desync_frames_bucket_total{bucket="1_2"} 1810
telemt_desync_frames_bucket_total{bucket="3_10"} 2837
telemt_desync_frames_bucket_total{bucket="gt_10"} 2670
telemt_pool_swap_total 14
telemt_pool_force_close_total 764
telemt_me_writer_close_signal_drop_total 186
telemt_me_draining_writers_reap_progress_total 5481
telemt_me_writer_removed_unexpected_total 415
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 756
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5062
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 433
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 331
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4717
telemt_me_writer_teardown_success_total{mode="normal"} 5818
telemt_me_writer_teardown_noop_total 5491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 9058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 9997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 10281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 10605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 10939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 11189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 11306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 11309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 11309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 11309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 11309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 11309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 11309
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.867126
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 11309
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 186
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 395
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 2742626
telemt_user_connections_current{user="hello"} 5514
telemt_user_octets_from_client{user="hello"} 29715926152 (27.68 GB)
telemt_user_octets_to_client{user="hello"} 727439193332 (677.48 GB)
telemt_user_unique_ips_current{user="hello"} 1829
telemt_user_unique_ips_recent_window{user="hello"} 712
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 5373.9 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2059683
telemt_connections_bad_total 43860
telemt_connections_current 5976
telemt_connections_me_current 5976
telemt_handshake_timeouts_total 21513
telemt_upstream_connect_attempt_total 7951
telemt_upstream_connect_success_total 7585
telemt_upstream_connect_fail_total 262
telemt_upstream_connect_attempts_per_request{bucket="1"} 7847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5711
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1681
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 262
telemt_me_keepalive_timeout_total 177
telemt_me_reconnect_attempts_total 303
telemt_me_reconnect_success_total 214
telemt_me_reader_eof_total 183
telemt_me_idle_close_by_peer_total 183
telemt_me_route_drop_no_conn_total 4165884
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1868694
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 40
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_me_writers_active_current 41
telemt_desync_total 2471
telemt_desync_full_logged_total 671
telemt_desync_suppressed_total 1800
telemt_desync_frames_bucket_total{bucket="1_2"} 516
telemt_desync_frames_bucket_total{bucket="3_10"} 1107
telemt_desync_frames_bucket_total{bucket="gt_10"} 848
telemt_pool_swap_total 3
telemt_pool_force_close_total 153
telemt_me_writer_close_signal_drop_total 52
telemt_me_draining_writers_reap_progress_total 1571
telemt_me_writer_removed_unexpected_total 226
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 334
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1461
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 92
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 61
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1418
telemt_me_writer_teardown_success_total{mode="normal"} 1795
telemt_me_writer_teardown_noop_total 1572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3367
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.017074
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3367
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 52
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 181
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 1873944
telemt_user_connections_current{user="hello"} 5976
telemt_user_octets_from_client{user="hello"} 7085778196 (6.60 GB)
telemt_user_octets_to_client{user="hello"} 58325835354 (54.32 GB)
telemt_user_msgs_from_client{user="hello"} 4517
telemt_user_msgs_to_client{user="hello"} 3964
telemt_user_unique_ips_current{user="hello"} 1752
telemt_user_unique_ips_recent_window{user="hello"} 954
```

## rdp-onedash.ru

```
telemt 3.3.28

telemt_uptime_seconds 5378.9 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1794797
telemt_connections_bad_total 122215
telemt_connections_current 5737
telemt_connections_me_current 5737
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 17094
telemt_upstream_connect_attempt_total 18720
telemt_upstream_connect_success_total 18713
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 18720
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5312
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 113
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 722
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 173
telemt_me_reconnect_success_total 53
telemt_me_reader_eof_total 50
telemt_me_idle_close_by_peer_total 50
telemt_me_route_drop_no_conn_total 3050851
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1517617
telemt_me_endpoint_quarantine_total 27
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 40
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
telemt_me_writers_active_current 43
telemt_desync_total 2404
telemt_desync_full_logged_total 690
telemt_desync_suppressed_total 1714
telemt_desync_frames_bucket_total{bucket="1_2"} 608
telemt_desync_frames_bucket_total{bucket="3_10"} 1028
telemt_desync_frames_bucket_total{bucket="gt_10"} 768
telemt_pool_swap_total 5
telemt_pool_force_close_total 145
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 49
telemt_me_draining_writers_reap_progress_total 1200
telemt_me_writer_removed_unexpected_total 48
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 133
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1084
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 124
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1055
telemt_me_writer_teardown_success_total{mode="normal"} 1217
telemt_me_writer_teardown_noop_total 1204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2421
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 113.317022
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2421
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 49
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 1532381
telemt_user_connections_current{user="hello"} 5737
telemt_user_octets_from_client{user="hello"} 10563107260 (9.84 GB)
telemt_user_octets_to_client{user="hello"} 110576388771 (102.98 GB)
telemt_user_msgs_from_client{user="hello"} 75809
telemt_user_msgs_to_client{user="hello"} 92195
telemt_user_unique_ips_current{user="hello"} 1864
telemt_user_unique_ips_recent_window{user="hello"} 813
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 4803.6 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96252
telemt_connections_bad_total 1040
telemt_connections_current 736
telemt_connections_me_current 736
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 1442
telemt_upstream_connect_attempt_total 3461
telemt_upstream_connect_success_total 3458
telemt_upstream_connect_attempts_per_request{bucket="1"} 3458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 893
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2451
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 105
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 187
telemt_me_reconnect_success_total 45
telemt_me_reader_eof_total 40
telemt_me_idle_close_by_peer_total 40
telemt_me_route_drop_no_conn_total 83391
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87787
telemt_me_endpoint_quarantine_total 35
telemt_me_single_endpoint_shadow_rotate_total 40
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 1
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
telemt_desync_total 231
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 86
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 5
telemt_pool_force_close_total 121
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 38
telemt_me_draining_writers_reap_progress_total 1508
telemt_me_writer_removed_unexpected_total 40
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 172
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1377
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 120
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1387
telemt_me_writer_teardown_success_total{mode="normal"} 1549
telemt_me_writer_teardown_noop_total 1508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3057
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.982468
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3057
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 38
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 31
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 88813
telemt_user_connections_current{user="hello"} 736
telemt_user_octets_from_client{user="hello"} 922762570 (880.01 MB)
telemt_user_octets_to_client{user="hello"} 16969908049 (15.80 GB)
telemt_user_msgs_from_client{user="hello"} 5317
telemt_user_msgs_to_client{user="hello"} 6420
telemt_user_unique_ips_current{user="hello"} 266
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## 4vps.su

```
telemt 3.3.28

telemt_uptime_seconds 5377.0 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 931126
telemt_connections_bad_total 65624
telemt_connections_current 7232
telemt_connections_me_current 7232
telemt_handshake_timeouts_total 31323
telemt_upstream_connect_attempt_total 1615
telemt_upstream_connect_success_total 1613
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1614
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 733
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 870
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 63
telemt_me_reconnect_success_total 63
telemt_me_reader_eof_total 64
telemt_me_idle_close_by_peer_total 64
telemt_me_route_drop_no_conn_total 396198
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 779538
telemt_me_endpoint_quarantine_total 23
telemt_me_single_endpoint_shadow_rotate_total 34
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
telemt_me_writers_active_current 43
telemt_desync_total 2753
telemt_desync_full_logged_total 788
telemt_desync_suppressed_total 1965
telemt_desync_frames_bucket_total{bucket="1_2"} 599
telemt_desync_frames_bucket_total{bucket="3_10"} 1080
telemt_desync_frames_bucket_total{bucket="gt_10"} 1074
telemt_pool_swap_total 4
telemt_pool_force_close_total 164
telemt_me_writer_close_signal_drop_total 23
telemt_me_draining_writers_reap_progress_total 1330
telemt_me_writer_removed_unexpected_total 64
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 153
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1243
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 121
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1166
telemt_me_writer_teardown_success_total{mode="normal"} 1396
telemt_me_writer_teardown_noop_total 1331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2727
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.877160
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2727
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 23
telemt_me_writer_restored_same_endpoint_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 779044
telemt_user_connections_current{user="hello"} 7231
telemt_user_octets_from_client{user="hello"} 10416679468 (9.70 GB)
telemt_user_octets_to_client{user="hello"} 253742906556 (236.32 GB)
telemt_user_unique_ips_current{user="hello"} 2243
telemt_user_unique_ips_recent_window{user="hello"} 865
```