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

# Server Metrics 2026-03-22 09:44:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 45512.7 (12h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1158691
telemt_connections_bad_total 62933
telemt_connections_current 1766
telemt_connections_me_current 1766
telemt_handshake_timeouts_total 53418
telemt_upstream_connect_attempt_total 17772
telemt_upstream_connect_success_total 17771
telemt_upstream_connect_attempts_per_request{bucket="1"} 17771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11541
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 538
telemt_me_reconnect_success_total 271
telemt_me_reader_eof_total 270
telemt_me_idle_close_by_peer_total 270
telemt_me_route_drop_no_conn_total 620842
telemt_me_route_drop_channel_closed_total 258
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 964386
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_endpoint_quarantine_total 319
telemt_me_single_endpoint_shadow_rotate_total 366
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_desync_total 6770
telemt_desync_full_logged_total 1964
telemt_desync_suppressed_total 4806
telemt_desync_frames_bucket_total{bucket="1_2"} 1997
telemt_desync_frames_bucket_total{bucket="3_10"} 2556
telemt_desync_frames_bucket_total{bucket="gt_10"} 2217
telemt_pool_swap_total 50
telemt_pool_force_close_total 1437
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 173
telemt_me_draining_writers_reap_progress_total 16173
telemt_me_writer_removed_unexpected_total 267
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1119
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15260
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1407
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14736
telemt_me_writer_teardown_success_total{mode="normal"} 16379
telemt_me_writer_teardown_noop_total 16175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32554
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 67.231268
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32554
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 173
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 247
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 962619
telemt_user_connections_current{user="hello"} 1766
telemt_user_octets_from_client{user="hello"} 15124184084 (14.09 GB)
telemt_user_octets_to_client{user="hello"} 309508444484 (288.25 GB)
telemt_user_unique_ips_current{user="hello"} 626
telemt_user_unique_ips_recent_window{user="hello"} 236
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 58878.8 (16h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1754479
telemt_connections_bad_total 160179
telemt_connections_current 2832
telemt_connections_me_current 2832
telemt_handshake_timeouts_total 46410
telemt_upstream_connect_attempt_total 35162
telemt_upstream_connect_success_total 34703
telemt_upstream_connect_fail_total 404
telemt_upstream_connect_attempts_per_request{bucket="1"} 35107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15033
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 404
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 2750
telemt_me_reconnect_success_total 1237
telemt_me_reader_eof_total 1133
telemt_me_idle_close_by_peer_total 1133
telemt_me_route_drop_no_conn_total 976473
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1344641
telemt_me_endpoint_quarantine_total 505
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 465
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
telemt_me_writers_active_current 128
telemt_desync_total 5956
telemt_desync_full_logged_total 3422
telemt_desync_suppressed_total 2534
telemt_desync_frames_bucket_total{bucket="1_2"} 1332
telemt_desync_frames_bucket_total{bucket="3_10"} 2332
telemt_desync_frames_bucket_total{bucket="gt_10"} 2292
telemt_pool_swap_total 59
telemt_pool_force_close_total 1610
telemt_me_writer_close_signal_drop_total 135
telemt_me_draining_writers_reap_progress_total 23878
telemt_me_writer_removed_unexpected_total 1102
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2464
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22507
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1486
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 124
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22268
telemt_me_writer_teardown_success_total{mode="normal"} 24971
telemt_me_writer_teardown_noop_total 23878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48849
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.387447
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48849
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 135
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 1018
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 1350793
telemt_user_connections_current{user="hello"} 2832
telemt_user_octets_from_client{user="hello"} 19579320490 (18.23 GB)
telemt_user_octets_to_client{user="hello"} 426414935684 (397.13 GB)
telemt_user_msgs_from_client{user="hello"} 21111
telemt_user_msgs_to_client{user="hello"} 48002
telemt_user_unique_ips_current{user="hello"} 1578
telemt_user_unique_ips_recent_window{user="hello"} 669
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 133738.7 (37h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10486908
telemt_connections_bad_total 929270
telemt_connections_current 4729
telemt_connections_me_current 4729
telemt_handshake_timeouts_total 302032
telemt_upstream_connect_attempt_total 49101
telemt_upstream_connect_success_total 49021
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 49029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26646
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 197
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2055
telemt_me_reconnect_success_total 1053
telemt_me_reader_eof_total 1046
telemt_me_idle_close_by_peer_total 1045
telemt_me_route_drop_no_conn_total 6518856
telemt_me_route_drop_channel_closed_total 87
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8271395
telemt_me_endpoint_quarantine_total 851
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 998
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_desync_total 35506
telemt_desync_full_logged_total 11579
telemt_desync_suppressed_total 23927
telemt_desync_frames_bucket_total{bucket="1_2"} 7909
telemt_desync_frames_bucket_total{bucket="3_10"} 13794
telemt_desync_frames_bucket_total{bucket="gt_10"} 13803
telemt_pool_swap_total 144
telemt_pool_force_close_total 4820
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 738
telemt_me_draining_writers_reap_progress_total 44786
telemt_me_writer_removed_unexpected_total 1004
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3799
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41441
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4497
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 323
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39966
telemt_me_writer_teardown_success_total{mode="normal"} 45240
telemt_me_writer_teardown_noop_total 44830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90070
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 200.461754
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90070
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 738
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 925
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 8261091
telemt_user_connections_current{user="hello"} 4729
telemt_user_octets_from_client{user="hello"} 132662525912 (123.55 GB)
telemt_user_octets_to_client{user="hello"} 2642442513548 (2.40 TB)
telemt_user_unique_ips_current{user="hello"} 1839
telemt_user_unique_ips_recent_window{user="hello"} 720
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 133740.2 (37h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8425882
telemt_connections_bad_total 764260
telemt_connections_current 4478
telemt_connections_me_current 4478
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 266211
telemt_upstream_connect_attempt_total 55281
telemt_upstream_connect_success_total 54787
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 55037
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26831
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 109
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 3005
telemt_me_reconnect_success_total 1172
telemt_me_reader_eof_total 1079
telemt_me_idle_close_by_peer_total 1079
telemt_me_route_drop_no_conn_total 2916337
telemt_me_route_drop_channel_closed_total 346
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6233630
telemt_me_endpoint_quarantine_total 849
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 1028
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_me_writers_active_current 47
telemt_desync_total 28515
telemt_desync_full_logged_total 9698
telemt_desync_suppressed_total 18817
telemt_desync_frames_bucket_total{bucket="1_2"} 6895
telemt_desync_frames_bucket_total{bucket="3_10"} 11043
telemt_desync_frames_bucket_total{bucket="gt_10"} 10577
telemt_pool_swap_total 145
telemt_pool_force_close_total 4395
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 487
telemt_me_draining_writers_reap_progress_total 43141
telemt_me_writer_removed_unexpected_total 1096
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3727
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40404
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4098
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 297
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38746
telemt_me_writer_teardown_success_total{mode="normal"} 44131
telemt_me_writer_teardown_noop_total 43147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87278
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 62.890639
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87278
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 487
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 995
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 6155801
telemt_user_connections_current{user="hello"} 4478
telemt_user_octets_from_client{user="hello"} 166446863163 (155.02 GB)
telemt_user_octets_to_client{user="hello"} 2925054830982 (2.66 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1815
telemt_user_unique_ips_recent_window{user="hello"} 583
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 133704.0 (37h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8077499
telemt_connections_bad_total 677659
telemt_connections_current 3911
telemt_connections_me_current 3911
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 264183
telemt_upstream_connect_attempt_total 59851
telemt_upstream_connect_success_total 59158
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 59305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27883
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 973
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1356
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3416
telemt_me_reconnect_success_total 1457
telemt_me_reader_eof_total 1346
telemt_me_idle_close_by_peer_total 1346
telemt_me_route_drop_no_conn_total 3344212
telemt_me_route_drop_channel_closed_total 216
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6029550
telemt_me_endpoint_quarantine_total 923
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 980
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 50
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
telemt_desync_total 28201
telemt_desync_full_logged_total 9592
telemt_desync_suppressed_total 18609
telemt_desync_frames_bucket_total{bucket="1_2"} 6809
telemt_desync_frames_bucket_total{bucket="3_10"} 10834
telemt_desync_frames_bucket_total{bucket="gt_10"} 10558
telemt_pool_swap_total 141
telemt_pool_force_close_total 4281
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 504
telemt_me_draining_writers_reap_progress_total 44084
telemt_me_writer_removed_unexpected_total 1372
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4128
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41283
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3902
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 379
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39803
telemt_me_writer_teardown_success_total{mode="normal"} 45411
telemt_me_writer_teardown_noop_total 44101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89512
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.293692
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89512
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 504
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 1283
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 6022099
telemt_user_connections_current{user="hello"} 3911
telemt_user_octets_from_client{user="hello"} 152505949587 (142.03 GB)
telemt_user_octets_to_client{user="hello"} 2643090696399 (2.40 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1558
telemt_user_unique_ips_recent_window{user="hello"} 558
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 3984.1 (1h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1648406
telemt_connections_bad_total 128232
telemt_connections_current 6336
telemt_connections_me_current 6336
telemt_handshake_timeouts_total 20535
telemt_upstream_connect_attempt_total 8103
telemt_upstream_connect_success_total 7684
telemt_upstream_connect_fail_total 338
telemt_upstream_connect_attempts_per_request{bucket="1"} 8022
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3679
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1333
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2670
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 338
telemt_me_keepalive_timeout_total 188
telemt_me_reconnect_attempts_total 315
telemt_me_reconnect_success_total 113
telemt_me_reader_eof_total 62
telemt_me_idle_close_by_peer_total 62
telemt_me_route_drop_no_conn_total 3611248
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1363563
telemt_me_endpoint_quarantine_total 23
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 35
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
telemt_me_writers_active_current 43
telemt_desync_total 2250
telemt_desync_full_logged_total 558
telemt_desync_suppressed_total 1692
telemt_desync_frames_bucket_total{bucket="1_2"} 438
telemt_desync_frames_bucket_total{bucket="3_10"} 865
telemt_desync_frames_bucket_total{bucket="gt_10"} 947
telemt_pool_swap_total 3
telemt_pool_force_close_total 125
telemt_me_writer_close_signal_drop_total 59
telemt_me_draining_writers_reap_progress_total 1051
telemt_me_writer_removed_unexpected_total 106
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 181
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 976
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 80
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 926
telemt_me_writer_teardown_success_total{mode="normal"} 1157
telemt_me_writer_teardown_noop_total 1051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2208
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.553810
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2208
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 59
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 68
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 1369532
telemt_user_connections_current{user="hello"} 6336
telemt_user_octets_from_client{user="hello"} 8014777950 (7.46 GB)
telemt_user_octets_to_client{user="hello"} 41217061515 (38.39 GB)
telemt_user_msgs_from_client{user="hello"} 6014
telemt_user_msgs_to_client{user="hello"} 4995
telemt_user_unique_ips_current{user="hello"} 2320
telemt_user_unique_ips_recent_window{user="hello"} 1318
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 133710.9 (37h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7699555
telemt_connections_bad_total 684021
telemt_connections_current 4863
telemt_connections_me_current 4863
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 158569
telemt_upstream_connect_attempt_total 75970
telemt_upstream_connect_success_total 75144
telemt_upstream_connect_fail_total 706
telemt_upstream_connect_attempts_per_request{bucket="1"} 75850
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45755
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28945
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 443
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 706
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70462
telemt_me_reconnect_success_total 2080
telemt_me_reader_eof_total 1825
telemt_me_idle_close_by_peer_total 1824
telemt_me_route_drop_no_conn_total 3123016
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6062678
telemt_me_endpoint_quarantine_total 896
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1008
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 30690
telemt_desync_full_logged_total 10621
telemt_desync_suppressed_total 20069
telemt_desync_frames_bucket_total{bucket="1_2"} 6204
telemt_desync_frames_bucket_total{bucket="3_10"} 11776
telemt_desync_frames_bucket_total{bucket="gt_10"} 12710
telemt_pool_swap_total 139
telemt_pool_force_close_total 4031
telemt_pool_stale_pick_total 66
telemt_me_writer_close_signal_drop_total 483
telemt_me_draining_writers_reap_progress_total 46302
telemt_me_writer_removed_unexpected_total 1854
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4717
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43466
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3544
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 487
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42271
telemt_me_writer_teardown_success_total{mode="normal"} 48183
telemt_me_writer_teardown_noop_total 46303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94486
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.698307
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94486
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 483
telemt_me_refill_failed_total 4230
telemt_me_writer_restored_same_endpoint_total 1726
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 6060385
telemt_user_connections_current{user="hello"} 4863
telemt_user_octets_from_client{user="hello"} 150740613695 (140.39 GB)
telemt_user_octets_to_client{user="hello"} 2470201355663 (2.25 TB)
telemt_user_msgs_from_client{user="hello"} 115484
telemt_user_msgs_to_client{user="hello"} 517108
telemt_user_unique_ips_current{user="hello"} 1906
telemt_user_unique_ips_recent_window{user="hello"} 615
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 70546.8 (19h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6422673
telemt_connections_bad_total 247452
telemt_connections_current 3734
telemt_connections_me_current 3734
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2601027
telemt_upstream_connect_attempt_total 37367
telemt_upstream_connect_success_total 37103
telemt_upstream_connect_fail_total 257
telemt_upstream_connect_attempts_per_request{bucket="1"} 37360
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15203
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 257
telemt_me_reconnect_attempts_total 47487
telemt_me_reconnect_success_total 1258
telemt_me_reader_eof_total 921
telemt_me_idle_close_by_peer_total 921
telemt_me_route_drop_no_conn_total 1705791
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3194447
telemt_me_endpoint_quarantine_total 489
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 54
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 54
telemt_me_single_endpoint_shadow_rotate_total 541
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 17491
telemt_desync_full_logged_total 5896
telemt_desync_suppressed_total 11595
telemt_desync_frames_bucket_total{bucket="1_2"} 3502
telemt_desync_frames_bucket_total{bucket="3_10"} 6691
telemt_desync_frames_bucket_total{bucket="gt_10"} 7298
telemt_pool_swap_total 75
telemt_pool_force_close_total 2279
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 218
telemt_me_draining_writers_reap_progress_total 25345
telemt_me_writer_removed_unexpected_total 991
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2214
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24145
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1960
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 319
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23066
telemt_me_writer_teardown_success_total{mode="normal"} 26359
telemt_me_writer_teardown_noop_total 25351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51710
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.844937
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51710
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 218
telemt_me_refill_failed_total 2688
telemt_me_writer_restored_same_endpoint_total 1122
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3194767
telemt_user_connections_current{user="hello"} 3734
telemt_user_octets_from_client{user="hello"} 79152557476 (73.72 GB)
telemt_user_octets_to_client{user="hello"} 1360785926706 (1.24 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1575
telemt_user_unique_ips_recent_window{user="hello"} 596
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 51517.7 (14h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 493617
telemt_connections_bad_total 3700
telemt_connections_current 888
telemt_connections_me_current 888
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 9216
telemt_upstream_connect_attempt_total 27298
telemt_upstream_connect_success_total 27235
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 27293
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12732
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14231
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 272
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 1129
telemt_me_reconnect_success_total 454
telemt_me_reader_eof_total 452
telemt_me_idle_close_by_peer_total 452
telemt_me_route_drop_no_conn_total 160933
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 445786
telemt_me_endpoint_quarantine_total 480
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 442
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_desync_total 2121
telemt_desync_full_logged_total 625
telemt_desync_suppressed_total 1496
telemt_desync_frames_bucket_total{bucket="1_2"} 631
telemt_desync_frames_bucket_total{bucket="3_10"} 816
telemt_desync_frames_bucket_total{bucket="gt_10"} 674
telemt_pool_swap_total 55
telemt_pool_force_close_total 1299
telemt_me_writer_close_signal_drop_total 62
telemt_me_draining_writers_reap_progress_total 22066
telemt_me_writer_removed_unexpected_total 435
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1622
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20896
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1248
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20767
telemt_me_writer_teardown_success_total{mode="normal"} 22518
telemt_me_writer_teardown_noop_total 22066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44584
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.148667
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44584
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 62
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 401
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 447861
telemt_user_connections_current{user="hello"} 888
telemt_user_octets_from_client{user="hello"} 9010004517 (8.39 GB)
telemt_user_octets_to_client{user="hello"} 220101517483 (204.99 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 305
telemt_user_unique_ips_recent_window{user="hello"} 281
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 133715.2 (37h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9463315
telemt_connections_bad_total 1103609
telemt_connections_current 5251
telemt_connections_me_current 5251
telemt_handshake_timeouts_total 257379
telemt_upstream_connect_attempt_total 51624
telemt_upstream_connect_success_total 51426
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 51578
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25948
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_reconnect_attempts_total 1922
telemt_me_reconnect_success_total 1050
telemt_me_reader_eof_total 1022
telemt_me_idle_close_by_peer_total 1022
telemt_me_route_drop_no_conn_total 2680806
telemt_me_route_drop_channel_closed_total 69
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7024506
telemt_me_endpoint_quarantine_total 945
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1014
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 28394
telemt_desync_full_logged_total 9305
telemt_desync_suppressed_total 19089
telemt_desync_frames_bucket_total{bucket="1_2"} 7016
telemt_desync_frames_bucket_total{bucket="3_10"} 10337
telemt_desync_frames_bucket_total{bucket="gt_10"} 11041
telemt_pool_swap_total 148
telemt_pool_force_close_total 3993
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 486
telemt_me_draining_writers_reap_progress_total 46578
telemt_me_writer_removed_unexpected_total 982
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3741
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43850
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3885
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 108
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42585
telemt_me_writer_teardown_success_total{mode="normal"} 47591
telemt_me_writer_teardown_noop_total 46580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94171
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.925798
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94171
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 486
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 921
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 6997033
telemt_user_connections_current{user="hello"} 5251
telemt_user_octets_from_client{user="hello"} 135800923152 (126.47 GB)
telemt_user_octets_to_client{user="hello"} 3273737538724 (2.98 TB)
telemt_user_unique_ips_current{user="hello"} 1933
telemt_user_unique_ips_recent_window{user="hello"} 704
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 133711.9 (37h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8220169
telemt_connections_bad_total 917269
telemt_connections_current 4506
telemt_connections_me_current 4506
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 215338
telemt_upstream_connect_attempt_total 76113
telemt_upstream_connect_success_total 75576
telemt_upstream_connect_fail_total 468
telemt_upstream_connect_attempts_per_request{bucket="1"} 76044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42241
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30460
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1966
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 468
telemt_me_reconnect_attempts_total 6500
telemt_me_reconnect_success_total 1516
telemt_me_reader_eof_total 1347
telemt_me_idle_close_by_peer_total 1347
telemt_me_seq_mismatch_total 63
telemt_me_route_drop_no_conn_total 2880475
telemt_me_route_drop_channel_closed_total 246
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6266649
telemt_me_endpoint_quarantine_total 1044
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 34
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 34
telemt_me_single_endpoint_shadow_rotate_total 1014
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_desync_total 27406
telemt_desync_full_logged_total 9079
telemt_desync_suppressed_total 18327
telemt_desync_frames_bucket_total{bucket="1_2"} 6734
telemt_desync_frames_bucket_total{bucket="3_10"} 10091
telemt_desync_frames_bucket_total{bucket="gt_10"} 10581
telemt_pool_swap_total 145
telemt_pool_force_close_total 3920
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 484
telemt_me_draining_writers_reap_progress_total 45250
telemt_me_writer_removed_unexpected_total 1364
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4386
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42290
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3633
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 287
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41330
telemt_me_writer_teardown_success_total{mode="normal"} 46676
telemt_me_writer_teardown_noop_total 45254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91930
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.427768
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91930
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 484
telemt_me_refill_failed_total 287
telemt_me_writer_restored_same_endpoint_total 1185
telemt_me_writer_restored_fallback_total 87
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 6275108
telemt_user_connections_current{user="hello"} 4506
telemt_user_octets_from_client{user="hello"} 114712613621 (106.83 GB)
telemt_user_octets_to_client{user="hello"} 2671541827079 (2.43 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1840
telemt_user_unique_ips_recent_window{user="hello"} 637
```