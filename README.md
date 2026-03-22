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

# Server Metrics 2026-03-22 23:29:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 94969.9 (26h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3391406
telemt_connections_bad_total 275594
telemt_connections_current 780
telemt_connections_me_current 780
telemt_handshake_timeouts_total 106801
telemt_upstream_connect_attempt_total 35008
telemt_upstream_connect_success_total 35007
telemt_upstream_connect_attempts_per_request{bucket="1"} 35007
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22783
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 1360
telemt_me_reconnect_success_total 568
telemt_me_reader_eof_total 584
telemt_me_idle_close_by_peer_total 584
telemt_me_route_drop_no_conn_total 2969567
telemt_me_route_drop_channel_closed_total 1230
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2825594
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 653
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 740
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
telemt_me_writers_active_current 46
telemt_desync_total 12083
telemt_desync_full_logged_total 3791
telemt_desync_suppressed_total 8292
telemt_desync_frames_bucket_total{bucket="1_2"} 3248
telemt_desync_frames_bucket_total{bucket="3_10"} 4414
telemt_desync_frames_bucket_total{bucket="gt_10"} 4421
telemt_pool_swap_total 105
telemt_pool_force_close_total 3273
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 639
telemt_me_draining_writers_reap_progress_total 32062
telemt_me_writer_removed_unexpected_total 564
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2331
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29942
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3217
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28789
telemt_me_writer_teardown_success_total{mode="normal"} 32273
telemt_me_writer_teardown_noop_total 32073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64346
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 374.240668
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64346
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 639
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 507
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2814865
telemt_user_connections_current{user="hello"} 780
telemt_user_octets_from_client{user="hello"} 40353164044 (37.58 GB)
telemt_user_octets_to_client{user="hello"} 766127647932 (713.51 GB)
telemt_user_unique_ips_current{user="hello"} 355
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 108336.1 (30h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3967713
telemt_connections_bad_total 360659
telemt_connections_current 159
telemt_connections_me_current 159
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100166
telemt_upstream_connect_attempt_total 67057
telemt_upstream_connect_success_total 66246
telemt_upstream_connect_fail_total 719
telemt_upstream_connect_attempts_per_request{bucket="1"} 66965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28908
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 719
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9726
telemt_me_reconnect_success_total 3512
telemt_me_reader_eof_total 3521
telemt_me_idle_close_by_peer_total 3521
telemt_me_route_drop_no_conn_total 3637632
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3155634
telemt_me_endpoint_quarantine_total 825
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 41
telemt_me_single_endpoint_outage_exit_total 41
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 840
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
telemt_me_writers_active_current 43
telemt_desync_total 12877
telemt_desync_full_logged_total 7215
telemt_desync_suppressed_total 5662
telemt_desync_frames_bucket_total{bucket="1_2"} 2913
telemt_desync_frames_bucket_total{bucket="3_10"} 5053
telemt_desync_frames_bucket_total{bucket="gt_10"} 4911
telemt_pool_swap_total 100
telemt_pool_force_close_total 2975
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 244
telemt_me_draining_writers_reap_progress_total 43806
telemt_me_writer_removed_unexpected_total 3456
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5955
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41335
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2517
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40831
telemt_me_writer_teardown_success_total{mode="normal"} 47290
telemt_me_writer_teardown_noop_total 43807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91097
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.542765
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91097
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 244
telemt_me_refill_failed_total 238
telemt_me_writer_restored_same_endpoint_total 3158
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 3168121
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 42808182582 (39.87 GB)
telemt_user_octets_to_client{user="hello"} 784186972412 (730.33 GB)
telemt_user_msgs_from_client{user="hello"} 47428
telemt_user_msgs_to_client{user="hello"} 180951
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 183196.1 (50h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16262142
telemt_connections_bad_total 1631037
telemt_connections_current 853
telemt_connections_me_current 853
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 396552
telemt_upstream_connect_attempt_total 81553
telemt_upstream_connect_success_total 81453
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 81470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39608
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1704
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2929
telemt_me_reconnect_success_total 1526
telemt_me_reader_eof_total 1471
telemt_me_idle_close_by_peer_total 1469
telemt_me_route_drop_no_conn_total 14036118
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12921695
telemt_me_endpoint_quarantine_total 1193
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1373
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_me_writers_active_current 44
telemt_desync_total 53393
telemt_desync_full_logged_total 16943
telemt_desync_suppressed_total 36450
telemt_desync_frames_bucket_total{bucket="1_2"} 11868
telemt_desync_frames_bucket_total{bucket="3_10"} 20796
telemt_desync_frames_bucket_total{bucket="gt_10"} 20729
telemt_pool_swap_total 198
telemt_pool_force_close_total 6579
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1051
telemt_me_draining_writers_reap_progress_total 61248
telemt_me_writer_removed_unexpected_total 1418
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5296
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56642
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6109
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54669
telemt_me_writer_teardown_success_total{mode="normal"} 61938
telemt_me_writer_teardown_noop_total 61301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 112184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 115748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 117520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 119911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 121578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 122629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 123200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 123230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 123231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 123235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 123237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 123239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 123239
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.416557
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 123239
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1051
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 1319
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 12921904
telemt_user_connections_current{user="hello"} 853
telemt_user_octets_from_client{user="hello"} 190639436949 (177.55 GB)
telemt_user_octets_to_client{user="hello"} 3476054197831 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 415
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 183197.4 (50h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11805307
telemt_connections_bad_total 1218480
telemt_connections_current 650
telemt_connections_me_current 650
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344237
telemt_upstream_connect_attempt_total 96040
telemt_upstream_connect_success_total 94727
telemt_upstream_connect_fail_total 865
telemt_upstream_connect_attempts_per_request{bucket="1"} 95592
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39534
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3797
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 865
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4344
telemt_me_reconnect_success_total 1833
telemt_me_reader_eof_total 1696
telemt_me_idle_close_by_peer_total 1696
telemt_me_route_drop_no_conn_total 4548208
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8772924
telemt_me_endpoint_quarantine_total 1200
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1396
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_desync_total 38632
telemt_desync_full_logged_total 13002
telemt_desync_suppressed_total 25630
telemt_desync_frames_bucket_total{bucket="1_2"} 9553
telemt_desync_frames_bucket_total{bucket="3_10"} 14846
telemt_desync_frames_bucket_total{bucket="gt_10"} 14233
telemt_pool_swap_total 195
telemt_pool_force_close_total 5940
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 706
telemt_me_draining_writers_reap_progress_total 59608
telemt_me_writer_removed_unexpected_total 1729
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5415
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55775
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5428
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53668
telemt_me_writer_teardown_success_total{mode="normal"} 61190
telemt_me_writer_teardown_noop_total 59633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 114105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 117303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 118448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 119639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 120398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 120738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 120813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 120815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 120821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 120823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 120823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 120823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 120823
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.285299
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 120823
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 1564
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 8710726
telemt_user_connections_current{user="hello"} 650
telemt_user_octets_from_client{user="hello"} 217487268412 (202.55 GB)
telemt_user_octets_to_client{user="hello"} 3944540602367 (3.59 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 299
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 183161.6 (50h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11000268
telemt_connections_bad_total 963129
telemt_connections_current 537
telemt_connections_me_current 537
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345152
telemt_upstream_connect_attempt_total 80160
telemt_upstream_connect_success_total 78607
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 78812
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37953
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2014
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2358
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5667
telemt_me_reconnect_success_total 2314
telemt_me_reader_eof_total 2054
telemt_me_idle_close_by_peer_total 2053
telemt_me_route_drop_no_conn_total 5330071
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8321412
telemt_me_endpoint_quarantine_total 1280
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1350
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
telemt_desync_total 37932
telemt_desync_full_logged_total 12578
telemt_desync_suppressed_total 25354
telemt_desync_frames_bucket_total{bucket="1_2"} 9579
telemt_desync_frames_bucket_total{bucket="3_10"} 14507
telemt_desync_frames_bucket_total{bucket="gt_10"} 13846
telemt_pool_swap_total 191
telemt_pool_force_close_total 5847
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 736
telemt_me_draining_writers_reap_progress_total 59841
telemt_me_writer_removed_unexpected_total 2208
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6141
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55836
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5276
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53994
telemt_me_writer_teardown_success_total{mode="normal"} 61977
telemt_me_writer_teardown_noop_total 59912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 116071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 118782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 119734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 120807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 121408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 121622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 121750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 121781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 121789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 121802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 121835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 121838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 121889
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.655501
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 121889
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 736
telemt_me_refill_failed_total 178
telemt_me_writer_restored_same_endpoint_total 2005
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 8313397
telemt_user_connections_current{user="hello"} 537
telemt_user_octets_from_client{user="hello"} 192347164847 (179.14 GB)
telemt_user_octets_to_client{user="hello"} 3457867693793 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 53441.6 (14h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11148482
telemt_connections_bad_total 667712
telemt_connections_current 1026
telemt_connections_me_current 1026
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 260125
telemt_upstream_connect_attempt_total 54447
telemt_upstream_connect_success_total 51639
telemt_upstream_connect_fail_total 1895
telemt_upstream_connect_attempts_per_request{bucket="1"} 53534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26712
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17409
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6001
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1895
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7404
telemt_me_reconnect_success_total 1135
telemt_me_reader_eof_total 707
telemt_me_idle_close_by_peer_total 706
telemt_me_route_drop_no_conn_total 25274520
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9259995
telemt_me_endpoint_quarantine_total 385
telemt_me_single_endpoint_outage_enter_total 85
telemt_me_single_endpoint_outage_exit_total 85
telemt_me_single_endpoint_outage_reconnect_attempt_total 158
telemt_me_single_endpoint_outage_reconnect_success_total 42
telemt_me_single_endpoint_quarantine_bypass_total 158
telemt_me_single_endpoint_shadow_rotate_total 424
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 16087
telemt_desync_full_logged_total 4326
telemt_desync_suppressed_total 11761
telemt_desync_frames_bucket_total{bucket="1_2"} 3065
telemt_desync_frames_bucket_total{bucket="3_10"} 6507
telemt_desync_frames_bucket_total{bucket="gt_10"} 6515
telemt_pool_swap_total 55
telemt_pool_force_close_total 1871
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 469
telemt_me_draining_writers_reap_progress_total 16243
telemt_me_writer_removed_unexpected_total 1024
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2272
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14935
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1564
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14372
telemt_me_writer_teardown_success_total{mode="normal"} 17207
telemt_me_writer_teardown_noop_total 16262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33469
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.495275
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33469
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 469
telemt_me_refill_failed_total 334
telemt_me_writer_restored_same_endpoint_total 733
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 283
telemt_user_connections_total{user="hello"} 9285489
telemt_user_connections_current{user="hello"} 1026
telemt_user_octets_from_client{user="hello"} 86371080006 (80.44 GB)
telemt_user_octets_to_client{user="hello"} 586044854213 (545.80 GB)
telemt_user_msgs_from_client{user="hello"} 67224
telemt_user_msgs_to_client{user="hello"} 56168
telemt_user_unique_ips_current{user="hello"} 420
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 183168.2 (50h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10937334
telemt_connections_bad_total 940047
telemt_connections_current 779
telemt_connections_me_current 779
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 241537
telemt_upstream_connect_attempt_total 108975
telemt_upstream_connect_success_total 107845
telemt_upstream_connect_fail_total 958
telemt_upstream_connect_attempts_per_request{bucket="1"} 108803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41464
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1356
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 958
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72788
telemt_me_reconnect_success_total 2999
telemt_me_reader_eof_total 2691
telemt_me_idle_close_by_peer_total 2689
telemt_me_route_drop_no_conn_total 5251561
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8630739
telemt_me_endpoint_quarantine_total 1220
telemt_me_single_endpoint_outage_enter_total 41
telemt_me_single_endpoint_outage_exit_total 41
telemt_me_single_endpoint_outage_reconnect_attempt_total 43
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 43
telemt_me_single_endpoint_shadow_rotate_total 1379
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_desync_total 46051
telemt_desync_full_logged_total 15763
telemt_desync_suppressed_total 30288
telemt_desync_frames_bucket_total{bucket="1_2"} 9349
telemt_desync_frames_bucket_total{bucket="3_10"} 17626
telemt_desync_frames_bucket_total{bucket="gt_10"} 19076
telemt_pool_swap_total 187
telemt_pool_force_close_total 5542
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 659
telemt_me_draining_writers_reap_progress_total 63911
telemt_me_writer_removed_unexpected_total 2722
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6646
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60020
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4793
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58369
telemt_me_writer_teardown_success_total{mode="normal"} 66666
telemt_me_writer_teardown_noop_total 63912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 128444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 129842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 130261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 130534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 130568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 130571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 130571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 130574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 130578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 130578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 130578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 130578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 130578
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.200209
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 130578
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 659
telemt_me_refill_failed_total 4297
telemt_me_writer_restored_same_endpoint_total 2530
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8633796
telemt_user_connections_current{user="hello"} 779
telemt_user_octets_from_client{user="hello"} 194148706941 (180.82 GB)
telemt_user_octets_to_client{user="hello"} 3297055496776 (3.00 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 365
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 120004.5 (33h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11622484
telemt_connections_bad_total 474502
telemt_connections_current 546
telemt_connections_me_current 546
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4752629
telemt_upstream_connect_attempt_total 57202
telemt_upstream_connect_success_total 56782
telemt_upstream_connect_fail_total 409
telemt_upstream_connect_attempts_per_request{bucket="1"} 57191
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25927
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 409
telemt_me_reconnect_attempts_total 48775
telemt_me_reconnect_success_total 1757
telemt_me_reader_eof_total 1425
telemt_me_idle_close_by_peer_total 1424
telemt_me_route_drop_no_conn_total 4079259
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5584592
telemt_me_endpoint_quarantine_total 795
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 916
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31374
telemt_desync_full_logged_total 10692
telemt_desync_suppressed_total 20682
telemt_desync_frames_bucket_total{bucket="1_2"} 6227
telemt_desync_frames_bucket_total{bucket="3_10"} 12375
telemt_desync_frames_bucket_total{bucket="gt_10"} 12772
telemt_pool_swap_total 127
telemt_pool_force_close_total 3784
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 373
telemt_me_draining_writers_reap_progress_total 43064
telemt_me_writer_removed_unexpected_total 1477
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3634
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40949
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3343
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39280
telemt_me_writer_teardown_success_total{mode="normal"} 44583
telemt_me_writer_teardown_noop_total 43071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87654
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.646489
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87654
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 373
telemt_me_refill_failed_total 2732
telemt_me_writer_restored_same_endpoint_total 1561
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5577189
telemt_user_connections_current{user="hello"} 546
telemt_user_octets_from_client{user="hello"} 118801047500 (110.64 GB)
telemt_user_octets_to_client{user="hello"} 2159231322938 (1.96 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 100975.2 (28h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1486146
telemt_connections_bad_total 36474
telemt_connections_current 457
telemt_connections_me_current 457
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 29618
telemt_upstream_connect_attempt_total 47218
telemt_upstream_connect_success_total 47067
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 47190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24883
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 778
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2157
telemt_me_reconnect_success_total 875
telemt_me_reader_eof_total 855
telemt_me_idle_close_by_peer_total 855
telemt_me_route_drop_no_conn_total 510567
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1319693
telemt_me_endpoint_quarantine_total 819
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 830
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
telemt_me_writers_active_current 43
telemt_desync_total 8445
telemt_desync_full_logged_total 2527
telemt_desync_suppressed_total 5918
telemt_desync_frames_bucket_total{bucket="1_2"} 2191
telemt_desync_frames_bucket_total{bucket="3_10"} 3256
telemt_desync_frames_bucket_total{bucket="gt_10"} 2998
telemt_pool_swap_total 109
telemt_pool_force_close_total 2806
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 156
telemt_me_draining_writers_reap_progress_total 39677
telemt_me_writer_removed_unexpected_total 827
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3108
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37431
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2718
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36871
telemt_me_writer_teardown_success_total{mode="normal"} 40539
telemt_me_writer_teardown_noop_total 39681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80220
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.073232
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80220
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 156
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 742
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 1315561
telemt_user_connections_current{user="hello"} 457
telemt_user_octets_from_client{user="hello"} 25687235057 (23.92 GB)
telemt_user_octets_to_client{user="hello"} 565744341775 (526.89 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 183172.7 (50h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13253643
telemt_connections_bad_total 1574494
telemt_connections_current 614
telemt_connections_me_current 614
telemt_handshake_timeouts_total 382920
telemt_upstream_connect_attempt_total 70781
telemt_upstream_connect_success_total 70437
telemt_upstream_connect_fail_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 70644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35431
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 207
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2802
telemt_me_reconnect_success_total 1425
telemt_me_reader_eof_total 1405
telemt_me_idle_close_by_peer_total 1405
telemt_me_route_drop_no_conn_total 4476658
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10011842
telemt_me_endpoint_quarantine_total 1269
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1380
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
telemt_desync_total 41838
telemt_desync_full_logged_total 13660
telemt_desync_suppressed_total 28178
telemt_desync_frames_bucket_total{bucket="1_2"} 10062
telemt_desync_frames_bucket_total{bucket="3_10"} 15385
telemt_desync_frames_bucket_total{bucket="gt_10"} 16391
telemt_pool_swap_total 203
telemt_pool_force_close_total 5488
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 670
telemt_me_draining_writers_reap_progress_total 63897
telemt_me_writer_removed_unexpected_total 1347
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5109
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60183
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5314
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58409
telemt_me_writer_teardown_success_total{mode="normal"} 65292
telemt_me_writer_teardown_noop_total 63899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 126600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 128299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 128682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 129058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 129178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 129191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 129191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 129191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 129191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 129191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 129191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 129191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 129191
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.698128
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 129191
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 670
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1250
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 9978581
telemt_user_connections_current{user="hello"} 614
telemt_user_octets_from_client{user="hello"} 194375269384 (181.03 GB)
telemt_user_octets_to_client{user="hello"} 4427856908020 (4.03 TB)
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 183169.3 (50h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11547735
telemt_connections_bad_total 1323503
telemt_connections_current 582
telemt_connections_me_current 582
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 307344
telemt_upstream_connect_attempt_total 97421
telemt_upstream_connect_success_total 96554
telemt_upstream_connect_fail_total 659
telemt_upstream_connect_attempts_per_request{bucket="1"} 97213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52544
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41030
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 659
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10225
telemt_me_reconnect_success_total 2510
telemt_me_reader_eof_total 2331
telemt_me_idle_close_by_peer_total 2330
telemt_me_seq_mismatch_total 90
telemt_me_route_drop_no_conn_total 5637175
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8915822
telemt_me_endpoint_quarantine_total 1446
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 50
telemt_me_single_endpoint_outage_exit_total 50
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 48
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 1383
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
telemt_me_writers_active_current 51
telemt_desync_total 41569
telemt_desync_full_logged_total 13353
telemt_desync_suppressed_total 28216
telemt_desync_frames_bucket_total{bucket="1_2"} 10712
telemt_desync_frames_bucket_total{bucket="3_10"} 15286
telemt_desync_frames_bucket_total{bucket="gt_10"} 15571
telemt_pool_swap_total 193
telemt_pool_force_close_total 5279
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 656
telemt_me_draining_writers_reap_progress_total 63811
telemt_me_writer_removed_unexpected_total 2368
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6473
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59788
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4808
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58532
telemt_me_writer_teardown_success_total{mode="normal"} 66261
telemt_me_writer_teardown_noop_total 63816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 127391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 129169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 129708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 130027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 130077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 130077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 130077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 130077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 130077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 130077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 130077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 130077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 130077
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.407392
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 130077
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 656
telemt_me_refill_failed_total 399
telemt_me_writer_restored_same_endpoint_total 2030
telemt_me_writer_restored_fallback_total 124
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 8921175
telemt_user_connections_current{user="hello"} 582
telemt_user_octets_from_client{user="hello"} 157041770765 (146.26 GB)
telemt_user_octets_to_client{user="hello"} 3471482354255 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 281
telemt_user_unique_ips_recent_window{user="hello"} 51
```